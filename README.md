SassPractice
============

Sass 101

1. Make sure you have Ruby installed on your machine. Run "ruby -v" in your command line to check. If you're using a Mac, Ruby comes pre-installed. You can refer to the Sass docs for more info on getting set up with Ruby. http://sass-lang.com/install

2. Next you need to install Ruby gems, a package manager for Ruby. Run "sudo gem install sass" in your command line. 

3. Make a new directory. Create an index.html file and a styles.scss file inside of it.

4. Set up Sass to watch for changes in your styles.scss file. Run "sass --watch styles.css:styles.css" in your command line. This will also create a styles.css file at the same time. In your command line you should see "Sass is watching for changes". Sass will now update your styles.css file as you save new changes to your styles.scss file.

5. Look back at our html-layout projects. Pick one to recreate using Sass. Try setting up some variabes and nesting your selectors like HTML. Try creating a mixin directive and passing it arguments.

This barely skims the surface of what Sass can do. Hopefully you caught a glimpse of how useful it can be and will try using it in a project.
