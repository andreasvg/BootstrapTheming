# BootstrapTheming

This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 6.2.5.

Example of how to easily theme Bootstrap using some SASS variables, and use the Bootstrap navbar without any reliance on jQuery or PopperJS.

### Required packages:

- ngx-bootstrap
- rxjs-compat
- bootstrap
- primeng
- primeicons

### Required modules for the navbar to work:

- BrowserModule
- FormsModule
- CollapseModule
- BsDropdownModule
- CalendarModule (from PrimeNg)

## Issues
Styling the PrimeNg date picker is a bit of a mare! We should be doing this locally to the component that uses the date picker but have not been able to get this to work yet. For now, the styling is performed at the root level in styles.scss. We also have way too many !important CSS rules...

## Development server

Run `ng serve` for a dev server. Navigate to `http://localhost:4200/`. The app will automatically reload if you change any of the source files.
