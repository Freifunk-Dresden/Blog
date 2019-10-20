# Freifunk-Dresden Blog
Blog der Webseite [https://blog.freifunk-dresden.de/](https://blog.freifunk-dresden.de/)

Um einen neuen Beitrag zu erstellen brauchst du keine weitere Software. Das Blog kannst du **direkt im Browser hier auf Github bearbeiten**.


> Falls du zu ungeduldig bist, erstelle bitte gerne einfach ein **[Issue](https://github.com/Freifunk-Dresden/Blog/issues)** mit deinem Text für den neuen Blog Eintrag. Wir erstellen dann daraus einen Beitrag. Aber **bitte** erst einmal diese **kurze Anleitung zuende lesen**. Es ist viel einfacher als es zuerst erscheinen mag :)

- Logge dich in deinem Github Account ein (oder falls du einen eigenen Account ablehnst, benutze den Username: `ffdd-blogger`, Passwort: `08blogger15`)

### 1. Klicke einfach oben auf den Ordner [`_posts`](https://github.com/Freifunk-Dresden/Blog/tree/master/_posts) und führe dann folgende Schritte aus:

  - Erstelle eine neue `.md` seite im ordner [`_posts`](https://github.com/Freifunk-Dresden/Blog/tree/master/_posts), drücke dazu rechts oben auf "Create new file":
     ![Create new file](https://raw.githubusercontent.com/Freifunk-Dresden/Blog/master/create_blog_post.png)
     (beim ersten mal wird dabei automatisch eine Kopie dieses Projekts in deinem Github erzeugt, in dem du ab dann arbeitest).
  - Die Benennung der Datei muss dabei mit dem **Datum** (JJJJ-MM-TT) beginnen, gefolgt von einem **Minus**, dann ein rein informativen **Teil der ignoriert wird** und dann **enden auf .md**, z.B. `2019-01-30-beschreibender-ignorierter-teil.md`
  - Der Inhalt der Datei muss anfangen mit den Zeilen:
 ```
 ---
 layout: post
 title: Hier der Titel deiner neuen Seite
 author:
 category: Sonstiges
 ---

 Hier Der Text für deinen neuen Blog Eintrag

 ```
  - Formatierungen können mit den Knöpfen über dem Eingabefeld erstellt werden
  - in dem Reiter "Preview changes" kannst du jederzeit überprüfen, wie dein Post aussehen würde.
  - Author: Das bist du dann sozusagen :)
  - **category: Stelle sicher das die Kategorie auch im Ordner `category` angelegt ist!**
  - optional: Bilder und Media-Files können in den Ordner `downloads` hochgeladen werden.
  - optional: weitere Formatierungen findet man wenn man nach *"markdown cheat sheet"* sucht, z.B. https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet

### 2. Wähle dann unten "Propose new file"
### 3. erstelle einen "Pull Request"
Wenn du fertig bist, erstelle einen "Pull Request" mit dem grünen Symbol, dadurch wird ein "Pull Request Issue" erstellt, in dem ein Mitglied des Freifunk Dresden - Blog Projekts deine Änderungen noch einmal anschauen kann und dann freigeben.
