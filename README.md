# sass_project
My working Sass framework

To use this:
<pre>
git clone --recursive https://github.com/mwailes11/sass_project [folder-name]
</pre>

To use as a sub-module:
<pre>
  git submodule add https://github.com/mwailes11/sass_project [folder-name]
</pre>

In each sub-directory, there is a
<pre>
  _manifest.scss
</pre>
Any file in a sub-directory should be imported into that directory's manifest. Those manifest files are then imported into the main scss file.
