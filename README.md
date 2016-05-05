# Consumers-Design-Pattern
Boiler Plate code for queue consumers, using Design Pattern: Singleton, Repository, Factory etc.

When we start writing queue consumer, we often mess up a lot of responsibility to single code base/script, which makes it harder
to maintain.

We can solve this problem by introducing command and service layer.

#### Command Layer
** This will handle the client/queue request.

** This will create the all infra dependency required for service to perform.

** And will finally delegate the command to service layer.

