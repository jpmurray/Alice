# Boiletplate

This is containing my usual setup for a new Laravel project.

## What does it include

-   Helper for artisan make commands (laracademy/interactive-make).
-   Backblaze B2 as a filesystem adapter (bringyourownideas/laravel-backblaze).
-   Backups configured to used the B2 adapter, and to run tasks at night _when in production_ (spatie/laravel-backup).

## What it does not include, but might want to

-   Any auth scaffholding (laravel/ui for Bootstrap, laravel/breeze for Tailwind).
-   My components, if I decided to use Tailwind (jpmurray/GoneWithTheWind)

## Usage

-   Clone repo and delete the `.git` folder, **or** download the zip file of this repo.
-   I should explore the `composer create-project` way...
