# module
<p>coppy file to: core/module</p>
<p>composer use: "Core\\Module\\":"core/module/src/"<p>
<p>composer run: composer dumpautoload</p>
<h3>Use view</h3>
<p>view('module::view').</p>
<p><i><u>Example:</u></i><p><p>
<code>
Route::get('/', function () {
  return view('blog::index');
});
</code>
</p>
<h3>Show list module</h3>
<p>php artisan module:list</p>
<h3>Create module</h3>
<p>php artisan module:create <module-name></p>
