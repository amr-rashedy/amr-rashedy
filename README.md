- š Hi, Iām @amr-rashedy
- š Iām interested in ...
- š± Iām currently learning ...
- šļø Iām looking to collaborate on ...
- š« How to reach me ...

<!---
amr-rashedy/amr-rashedy is a āØ special āØ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
//create laravel project
composer create-project laravel/laravel projectname "6.*"
//project run
php artisan serve
//route parameter must
rout::get('/pagename/{id}', function ($id) {
return $id;});
//route parameter optional
rout::get('/pagename/{id?}', function ($id) {
return $id;});
