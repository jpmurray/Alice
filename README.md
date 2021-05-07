# Alice

Alice is the beggining of the story. Thus, with Alice, I'm starting new Laravel projects, this is my usual boilerplate.

## What does it include

-   Helper for artisan make commands (laracademy/interactive-make).
- A self diagnostic tool, so we can be clear after a new project is created with Alice (beyondcode/laravel-self-diagnosis)
-   Backblaze B2 as a filesystem adapter (bringyourownideas/laravel-backblaze).
-   Backups configured to used the B2 adapter, and to run tasks at night _when in production env_ (spatie/laravel-backup).
-   Helper to monitor what goes under the hood _when in local env_ (laravel/telescope).
-   Another helper to monitor under the hood _when debug is enabled_ (itsgoingd/clockwork).

## What it does not include, but might want to

-   Any auth scaffholding (laravel/ui for Bootstrap, laravel/breeze for Tailwind).
-   My components, if I decided to use Tailwind (jpmurray/GoneWithTheWind)

## Usage

-   Clone repo and delete the `.git` folder, **or** download the zip file of this repo.
-   I should explore the `composer create-project` way...
