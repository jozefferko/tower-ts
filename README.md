# tower-ts
A functional typescript framework inspired by NestJS

## goals
+ Strictly type checked
  + everything is typechecked by default, its the user that has to go out of their way to disable typechecking
  + where possible apply runtime type-checking
+ opinionated
  + opinionated frameworks force everyone to use the same structure, which makes different parts of the system homogenous, making them easier to reason with
+ modular
  + code is split up into modules
  + a module should only import files from outside a module in its index file (including interfaces)
+ functional
  + embrace functional principles for all part of the system
+ simple
  + abstract all complexity away
  + if there is so much boilerplate you need a CLI tool, you failed
