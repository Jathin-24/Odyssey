# Odyssey: Beyond the Horizon

Ocean-themed event website built with Spring Boot, Thymeleaf, HTML and CSS.

## Run

Requires Java 17+ and Maven.

    mvn spring-boot:run

Then open http://localhost:8080

## Structure

- `HomeController.java` holds the event name, tagline and the four stages
- `Registration.java` is the JPA entity mapped to the `registrations` database table
- `RegistrationRepository.java` is the Spring Data JPA repository
- `RegistrationService.java` manages database persistence and queries
- `RegistrationController.java` handles `/register`, `/register/pass/{id}`, `/admin/registrations`, and `/api/registrations`
- `templates/index.html` is the home page
- `templates/register.html` is the Odyssey registration page
- `templates/pass.html` is the digital holographic boarding pass ticket
- `templates/admin.html` is the database manifest dashboard
- `static/css/style.css` is the base ocean theme
- `static/css/register.css` contains registration form and boarding pass styles
- `static/js/main.js` is the scroll reveal animation
- `static/js/register.js` manages track selection, team size dynamic fields, and form interaction

## Database & Endpoints

- **Web Portal**: http://localhost:8080/
- **Registration Form**: http://localhost:8080/register
- **Database Manifest Dashboard**: http://localhost:8080/admin/registrations
- **JSON API**: http://localhost:8080/api/registrations
- **Database Engine**: MySQL 8.0
  


# Odyssey
