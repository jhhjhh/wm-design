wm-design
=========

WM design repo, mostly styl files

These are the style files and javascript files that make the WM website work.

Need to use a minifier for base-min.css

Setup Workflow
--------------

cd Dropbox/git/wm-design/styles/
stylus -w -u nib base.styl

and then in the same directory

cleancss -o base-min.css base.css