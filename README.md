
# gform-superform-frontend

A gForms superform is a service that presents the user with a number of gforms to be filled in and submitted as one.  It is useful for:

- splitting up large forms into "sections", each of which is a gForm
- allowing each section to be completed independently of other sections
- allowing each section to optionally be repeated
- allowing sections of a large form to be completed by many different users
- allowing multiple gForms to be aggregated into a single submission 

From the users perspective, they are completing a single form comprising multiple, potentially repeating, independent sections.

The UX design for a superform is based on the GDS Design System Task List pattern.

Superforms are defined using different JSON to standard gForms, and are processed by a different microservice (gform-superform-frontend).

### License

This code is open source software licensed under the [Apache 2.0 License]("http://www.apache.org/licenses/LICENSE-2.0.html").
