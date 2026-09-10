# Mitt Webbprojekt
Lite mer smör är en personlig webbplats med mat- och recepttema. Syftet med webbplatsen är att samla webbplatsskaparens favoritrecept och tips på en plattform. Den innehåller bland annat recept, tips och en kontaktsida. 
## 🛠 Tekniker
Projektet är byggt med:
- HTML
- CSS
## 📰 Publicerade versioner
[Netlify](https://calm-torte-192002.netlify.app/)
[GitHub Pages](https://emmahulten.github.io/dt224g_emma_hulten/)

## 🔎 Git - Frågor & Svar
1. **Vad är skillnaden mellan git add och git commit?**
git add är det kommando som lägger till filen/filerna i Staging Area. De har då förberetts för att sparas på det lokala repot. 
git commit är nästa steg i processen. För att kunna göra en commit behöver filerna finnas redo på staging area. När man genomför en git commit anges ett commit-meddelande med information om den aktuella versionen, och sedan sparas denna på det lokala repot. En commit är en sparad version av projektet vid ett visst tillfälle, man kan senare se i loggen när och vem som genomfört denna commit, meddelandet som skrivits och ett unikt ID för versionen. 

2. **Varför använder man branches istället för att jobba direkt i main?**
Branches används för att kunna arbeta med utveckling och förbättring av koden på ett säkert sätt. Det används bland annat för att utveckla nya funktioner eller hantera buggar. När man jobbar på en branch som är separat från main kan man bygga och testa koden fullt ut utan att påverka koden i main. Det gör det enklare att samarbeta och minskar risken för problem med koden i main. 

3. **Vad händer rent praktiskt när man gör en merge?**
En merge innebär att Git sammanför utvecklingen från två branches så att ändringarna samt historiken från den ena branchen blir en del av den branch man står på. 

4. **Vad är skillnaden mellan att pusha till GitHub och att publicera direkt på t.ex. Netlify?**
Att genomföra en push till GitHub innebär att din kod skickas från ditt lokala repo till ditt remote repo. 
Att publicera direkt på tex Netlify innebär att du skickar webbplatsens filer till en webbserver/hostingtjänst, så att webbplatsen blir tillgänglig på internet. 
Om du redan publicerat webbplatsen på en plattform som du kopplat samman med ditt GitHub repository så kan det räcka med en push till GitHub för att plattformen ska uppdatera din webbplats. Detta då vissa plattformar stämmer av ev. ändringar i ditt remote repo. 

5. **Om du vill exkludera någon fil i projektet från versionshanteringen, hur gör du då?**
Man skapar en fil och döper den till .gitignore. I denna fil anger man sedan vilken/vilka filer och/eller mappar Git ska ignorera från versionshanteringen.
