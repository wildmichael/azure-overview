# [Integration]

* **[Service Bus]**: Messaging as a Service (MaaS).
    Kann zur Integration von On-Premise und Cloud-Anwendungen, zur
    Entkoppelung von Anwendungen, Ereignisversand an Backendsysteme, etc.
    verwendet werden. Im Gegensatz zu [Event Hubs](/analysis.md)
    ist hier der Fokus nicht auf Ereignissen, sondern auf Nachrichten mit
    Antworten. Gibt es als
    * Queue, ähnlich wie [Queue Storage](./storage.md) aber mit mehr
      Fähigkeiten, wie z.B. Transaktions-Semantik, wenn mehrere Nachrichten
      gruppiert werden, oder FIFO- und At-Most-Once-Garantien.
    * Topics, wenn mehrere Empfänger eine Nachrichten erhalten sollen
      (Publish-Subscribe).
* **[Event Grid]**: Event Bus, für die Erstellung von
    ereignisgesteuerten und serverlosen Anwendungen. Die Events selber sollten
    dabei nur Referenzen auf die eigentlichen Daten übermitteln. Geeignet für
    Einzelereignisse. Datenreihen (z.B. Zeitreihen von Messinstrumenten) sollten
    über [Event Hubs](./analysis.md), welche z.B. in ein Langzeitarchiv abgelegt
    und gleichzeitig mittels [Stream Analytics](./analysis.md) weiterverarbeitet
    werden sollen.
* **[Logic Apps]**: Nachfolger von BizTalk, mit Migrationstool, mit Container
    Deployment. Vielzahl von Konnektoren, komplexe Datentransformationen, B2B
    und Enterprise-Messaging.

[Integration]: https://azure.microsoft.com/de-de/services/#integration
[Service Bus]: https://azure.microsoft.com/de-de/services/service-bus/
[Event Grid]: https://azure.microsoft.com/de-de/services/event-grid/
[Logic Apps]: https://azure.microsoft.com/de-de/services/logic-apps/
