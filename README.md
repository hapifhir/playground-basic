# HAPI FHIR Playground: Basic

This project is a skeleton project for using [HAPI FHIR](https://hapifhir.io) to access a public [FHIR](http://hl7.org/fhir/) server hosted at [http://hapi.fhir.org/baseR4](http://hapi.fhir.org/baseR4).

### Getting Started:

* [ ] Take a few minutes to familiarize yourself with the [FHIR Standard](http://hl7.org/fhir/) for health data exchange. In particular you might want to read the [Executive Summary](http://hl7.org/fhir/summary.html) and the [Developer Introduction](http://hl7.org/fhir/overview-dev.html)

* [ ] Try clicking on the link below. It is a FHIR *Search* operation used to look for patients with the name "Smith". (This is a publically accessible test server used by people all over the world, so we don't control what data is on it. Sometimes you may find unexpected or weird data there.) 

  http://hapi.fhir.org/baseR4/Patient?family=SMITH
  
* [ ] Create your own GitHub project and copy the contents of this repository into your own project (please don't fork this repository)

* [ ] Locate the class `SampleClient` and run it. This class runs the same search shown above.

### Tasks:

* [ ] Modify `SampleClient` so that it prints the first and last name, and birth date of each Patient to the screen

* [ ] Sort the output so that the results are ordered by the patient's first name

* [ ] Commit your work 