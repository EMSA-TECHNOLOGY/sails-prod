# Upgrade node

* Must use async v1.5.2 (2.0.0 has a breaking changes  according to the async.auto)
* anchor (v0.10.5) is OK since latest has no the .to() (validate.js -> var invalidParams = anchor(req.params.all()).to({type: usage});)
