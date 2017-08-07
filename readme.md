<h1>Start HTML Template</h1>

<p>Gulp, Sass, Browsersync, Autoprefixer, Clean-CSS, Uglify, Imagemin, Vinyl-FTP and Bower (libs path). The template contains a <strong>.htaccess</strong> file with caching rules for web server.</p>

<h2>How to use OptimizedHTML</h2>

<ol>
	<li>Install Node Modules: <strong>npm i</strong>;</li>
	<li>Run the template: <strong>gulp</strong>.</li>
</ol>

<h2>Gulp tasks:</h2>

<ul>
	<li><strong>gulp</strong>: run default gulp task (sass, js, watch, browserSync) for web development;</li>
	<li><strong>build</strong>: build project to <strong>dist</strong> folder (cleanup, image optimize, removing unnecessary files);</li>
	<li><strong>deploy</strong>: project deployment on the server from <strong>dist</strong> folder via <strong>FTP</strong>;</li>
	<li><strong>rsync</strong>: project deployment on the server from <strong>dist</strong> folder via <strong>RSYNC</strong>;</li>
	<li><strong>clearcache</strong>: clear all gulp cache.</li>
</ul>

<h2>Rules for working with the starting HTML template</h2>

<ol>
	<li>For installing new library, just run the command "<strong>bower i plugin-name</strong>" in the terminal. Libraries are automatically placed in the folder <strong>app/libs</strong>. Then place library paths in the <strong>'libs'</strong> task (gulpfile.js);</li>
	<li>All custom JS located in <strong>app/js/common.js</strong>;</li>
	<li>All Sass vars placed in <strong>app/sass/_vars.sass</strong>;</li>
	<li>All CSS media queries placed in <strong>app/sass/_media.sass</strong>;</li>
	<li>All jQuery libraries CSS styles placed in <strong>app/sass/_libs.sass</strong>;</li>
	<li>Rename <strong>ht.access</strong> to <strong>.htaccess</strong> before place it in your web server. This file contain rules for files caching on web server.</li>
</ol>
