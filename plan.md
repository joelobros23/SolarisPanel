# Project Plan: SolarisPanel

**Description:** A simple and lightweight web hosting control panel designed for easy management of domains, built using Ruby on Rails, SQLite3, Tailwind CSS, and Devise.


## Development Goals

- [ ] Configure Tailwind CSS using `rails tailwindcss:install` and customize `app/javascript/application.js` to import the tailwind directives.
- [ ] Implement user authentication using Devise. Customize Devise views to integrate with Tailwind CSS for consistent styling.
- [ ] Modify the Domain model to include validations for `name`, `plan`, and `status`. Ensure `name` is unique.
- [ ] Implement the association between `User` and `Domain` models. A user should be able to own multiple domains.
- [ ] Customize the Domain scaffold views (index, show, new, edit) to use Tailwind CSS classes for improved UI and responsiveness.
- [ ] Implement a dashboard view that displays the logged-in user's domains and their status. This dashboard should be the default landing page after login.
- [ ] Add a simple user profile page where users can update their email and password. (Managed by Devise)
- [ ] Create a basic pricing plan system (e.g., free, basic, premium) and associate it with the `plan` attribute of the `Domain` model. Use a select box in the domain creation form.
- [ ] Add seed data for different plans (free, basic, premium) to facilitate testing and initial setup.
- [ ] Implement a simple domain status update feature (e.g., active, inactive, suspended) with a dropdown or similar control.
