[![Image](https://www.vipm.io/package/neosoft_technologies_inc_lib_open_dqmh_request_message_diagram/badge.svg?metric=installs)](https://www.vipm.io/package/neosoft_technologies_inc_lib_open_dqmh_request_message_diagram/) [![Image](https://www.vipm.io/package/neosoft_technologies_inc_lib_open_dqmh_request_message_diagram/badge.svg?metric=stars)](https://www.vipm.io/package/neosoft_technologies_inc_lib_open_dqmh_request_message_diagram/)

# Open-DQMH-Request-Message-Diagram
When writing code using DQMH Framework, the way you communicate between actors is by way of request message VIs. Each DQMH request message has a VI which collects the inputs for the message and transports it using custom user event, but the VI (which is often what you see on the block diagram) is not what gets executed by the DQMH module that receives the message. The actual logic that executes when the message is received resides in what we call a DQMH Request Message Diagram which is a member of the receiving DQMH module main VI.

In order to get from a request message VI (what you see on the block diagram) to the actual DQMH Request Message Diagram block diagram (where the true business logic your message resides) takes fewer different actions. Using our Right-Click Shortcut or our Quick Drop Ctrl-Key Shortcut (CTRL-K by default) allows developper to quickly open the Message Diagram of the Message Handling Loop within the DQMH Module Main VI from the DQMH Module Request or Request and Wait for Reply or Round Trip Broadcast methods on the block diagram.

# Source
Use LabVIEW 2017 SP1 to contribute to this repository. Configuration Manager will be maintained for LV 2017 and later versions for as long as features permit. If you are developing in more recent versions of LabVIEW, your contributions will not make it to master branch.