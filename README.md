# Portfolio

This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 13.2.6.

## Development server

Run `ng serve` for a dev server. Navigate to `http://localhost:4200/`. The app will automatically reload if you change any of the source files.

## Code scaffolding

Run `ng generate component component-name` to generate a new component. You can also use `ng generate directive|pipe|service|class|guard|interface|enum|module`.

## Build

Run `ng build` to build the project. The build artifacts will be stored in the `dist/` directory.

## Running unit tests

Run `ng test` to execute the unit tests via [Karma](https://karma-runner.github.io).

## Running end-to-end tests

Run `ng e2e` to execute the end-to-end tests via a platform of your choice. To use this command, you need to first add a package that implements end-to-end testing capabilities.

## Further help

To get more help on the Angular CLI use `ng help` or go check out the [Angular CLI Overview and Command Reference](https://angular.io/cli) page.

# Deployment

To deploy your Angular portfolio on GitHub Pages, you can follow these steps:

### 1. **Prepare Your Angular Project for Deployment**
   - Open your Angular project.
   - Run the following command to build the project:
     ```bash
     ng build --prod --output-path docs --base-href /your-repo-name/
     ```
     - `--output-path docs`: This builds your project into a folder named `docs`, which is required by GitHub Pages.
     - `--base-href /your-repo-name/`: Replace `your-repo-name` with the name of your GitHub repository.

### 2. **Configure GitHub Pages**
   - Push your project to GitHub.
   - Go to your repository on GitHub.
   - Click on the **Settings** tab.
   - Scroll down to the **Pages** section.
   - In the **Source** dropdown, select the `main` branch and the `/docs` folder.
   - Click **Save**.

### 3. **Access Your Deployed Portfolio**
   - After a few minutes, your portfolio should be available at `https://your-username.github.io/your-repo-name/`.

This will make your Angular portfolio live on GitHub Pages. Let me know if you need further assistance!

