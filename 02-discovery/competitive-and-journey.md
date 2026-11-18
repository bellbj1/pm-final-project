# Competitive Analysis & Journey Map (Module 2)

## Responses
- **Role, who are you solving for? (the specific user segment or profile):** Frontline delivery driver who uses the app repeatedly to execute routes and record completed deliveries.
- **Goal, what is this user ultimately trying to achieve?:** Complete each stop and record its outcome quickly, without unnecessary interaction at the doorstep.
- **Friction, the main barrier (moment of misery) stopping them from succeeding:** Moment of Misery: Diego stands at a doorstep in the rain, holding a package in one hand, and must navigate three screens to mark the stop delivered; he has started texting his dispatcher instead. This directly connects workflow complexity to abandonment of the intended process. Evidence: UXR-01; BUG-2055.
- **External tools, the outside platforms or tools the user is forced to use:** Workaround: Texting the Dispatcher Instead of Recording Delivery
The confirmed external tool is text messaging; the manual process is reporting completion directly to the dispatcher. UXR-01 does not identify the messaging app or explain what the dispatcher does afterward. WhatsApp appears in a separate dispatcher interview about route reassignment, so it should not be attributed to Diego.
- **The process, the 3 to 5 manual steps the user takes to get the job done:** Steps the Driver Takes
1. Reaches the delivery-completion step at the doorstep. Diego needs to mark a stop delivered while standing in the rain with a package in one hand.
2. Bypasses the app’s completion workflow. Rather than navigate three screens, he uses text messaging to contact his dispatcher.
3. Reports completion outside the product. The dispatcher receives the update through a separate communication channel rather than through the intended in-app process. Evidence: UXR-01; BUG-2055.
- **Core frustration, the exact moment the process feels most “broken”:** It reduces Diego’s immediate interaction burden but shifts coordination outside the product. A direct completion action becomes a person-to-person handoff. If the delivery must also be recorded in the application, someone must subsequently reconcile the message with the stop record—an additional step whose occurrence and duration have not been verified.

The workaround also separates the completion report from the route’s structured status. Unless that information is reconciled, dispatch cannot rely on the application alone for a complete operational picture. This is a risk created by the workaround, not evidence that texting causes the separately reported dashboard synchronization delays.
- **The evidence, a specific quote or behavior from the research that proves this:** The directly demonstrated consequence is workflow abandonment: Diego is still completing deliveries, but he is bypassing the product to report them. That supports the problem hook’s link between frontline complexity and reduced adoption. Across the broader research, an operations manager is evaluating a leaner competitor because essential functions are difficult to find, and a regional manager explicitly connects the daily driver experience to adoption problems and renewal risk. Evidence: UXR-04; UXR-10.

The defensible business connection is therefore completion friction → off-platform reporting → reduced reliance on the product, alongside broader evidence of competitive evaluation and renewal risk. Diego’s workaround illustrates that mechanism; it does not, by itself, prove customer churn or loss of market position.
- **Your journey map, a shareable link, or the map file you committed (e.g. journey-map.html):** https://github.com/bellbj1/pm-final-project/blob/main/02-discovery/journey-map.html
