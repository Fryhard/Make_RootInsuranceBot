# Make_RootInsuranceBot

## Notes for Dialogflow

* App's persona

* Entities
 * Pre-built, e.g time, number, address, etc
 * Developer, e.g. custom objects, e.g. anything things that we talk about

* Intent
 * 10 - 12 samples per intent
 * Not all the samples should contain the entity
  * This shows Google that not all of the phrases need to contain the entity

* Action
 * Parameters are auto determined based on the intents
 * Parameters can be makred as required


* Add web hook to be able to return dynamic content to the user
 * Return content based on the SurfaceCapabiliates of the device the user is using
  * This allows you return simple or complicated response back to the user.

* Use the try now in the API UI to check it
