## SOLID Priciple

#### S: Sigle Responsibility

- all the classes we create should have only 1 resposibility.
- that resposiblity only should be followed by that perticular class.
- How to know does any class have single resposibility or not?
  - just ask what that class does.
  - if that class has more than one resposiblity than its not following Single Responsibility priciple.

#### O: Open closed

- any Class or Interface should not be open for modification
- to add any functionality you should extend that class.

#### L: Liskov Substitution

- Liskov Substitution priciple states that whenever parent child relationship is there so both the class should be interchangable and subtitutable.
- if i pass object of parent or child it should be work of both.
- it should extent the capabilities of parent not reduce it.

#### I: Interface Segregation

- We should create interface such a way that those interfaces should have proper methed to be impletmented.
- we should not force the client/child class to impleted methods which are not required to it.

#### D: Dependency Inversion

- we should not have any dependency on any other modules.
- higher level modules should not have dependency on lower level modules

Examples: https://github.com/shabbirdwd53/design_patterns/tree/main/solid_principles
