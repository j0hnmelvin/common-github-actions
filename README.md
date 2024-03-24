# common-github-actions

## [Analyze Gradle Java Code](./.github/workflows/analyze-gradle-java-code.yml)
Analyzes Java code in Gradle project for the following:
- Unit Test Coverage Verification using JaCoCo
- Generate Unit Test Report using JaCoCo
- Static Code Analysis using SonarQube

## [Database Migration Gradle Flyway](./.github/workflows/database-migration-gradle-flyway.yml)
Migrates database using Flyway in Gradle project.

## [Deploy To Cloud Foundry With App Manifest](./.github/workflows/deploy-to-cloud-foundry-with-app-manifest.yml)
Deploys an application built in a previous step to Cloud Foundry using App Manifest.

## [Setup Headless Google Chrome](./.github/workflows/setup-headless-google-chrome.yml)
Install headless Google Chrome (i.e. Terminal or non-GUI browser) in GitHub Action's Runner.

Use cases for running headless browsers in a CI/CD pipeline:
- **Automated Testing**: Run tests on the web application to ensure functionality.
- **Visual Regression Testing**: Capture screenshots of the application UI to detect any unexpected visual changes.
- **Generating static site previews**: Pre-render the website's content for faster loading times and improved SEO. If your application is a static website, you can leverage a headless browser to pre-render the website's HTML, CSS, and JavaScript into a static format. This pre-rendered version can then be deployed, improving website loading speed and SEO.
- **Data scraping (with caution)**: Extract specific data from websites, but be mindful of terms of service and ethical considerations.