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

Todo
------------

Footer:

- [done] slightly bigger font
- search bar must on the right, aligned with the right side
- [done] plus d'espace entre les colomnes de pages/let'shang/FB like.
- Peux-etre pourrions nous separer ces differentes sections de footer avec une barre verticale, afin de rendre le footer plus structure?
- we need to sort out grid together

Menu bar:

- [done] le sous-menu bar (top, dress..etc) doit rester deplie/visible lorsque la personne clique sur un produit, pour qu'elle n'ait pas a recliquer sur 'shop' a chaque fois

Product collection page:

- titre du produit et le prix doivent etre aligne a gauche de la photo
- plus de whitespace entre photo et titre

Product page:
- la largeur de la page est tres petite, il faut donc mettre plus de white space entre la photo et le cote texte. De maniere plus generale, essayons de plus 'aerer' cette page
- font de la descripption doit etre un peu plus grand
- spread the joy doit etre aligne a la droite de page. 
- je veux un pin it bouton sur le coin droite en bas de la photo
- titre du produit: font must be slightly smaller

Added by James:

- Remove isotope from editorials
- make three wanderers youtube video responsive