## Learning Admin
Debonair Training Onboarding Software

### Installation Instruction
<ol>
<li>
Clone repository

```
git clone https://github.com/Abbasumaru/Laravel-project.git

cd learning-admin/
```
</li>
<li>
Copy example .env.example file

`cp .env.example .env`

Edit the following environment variables inside the newly copied `.env` file

```
APP_NAME="Learning Admin" <-- anything you want :)
APP_URL=http://learning-admin.test <-- should match the URL you want to access the app with
DB_DATABASE=learning_admin <-- database name
DB_USERNAME=root <-- database username
DB_PASSWORD=root <-- database password
```
</li>
<li>
Install composer dependencies

```
composer install <-- or composer update to update the dependencies
```
</li>
<li>
Migrate and seed database

```
php artisan migrate --seed <-- required to seed your database with dummy records for testing
```
</li>
</ol>
