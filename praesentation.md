<!-- Eingebettetes CSS -->
<style>
.custom-slide {
  display: flex;
  justify-content: space-between;
  align-items: flex-start;
  gap: 2em;
  padding: 1.5em;
  background: #eaf2f8;
  border-radius: 12px;
  box-shadow: 0 4px 16px rgba(0, 0, 0, 0.1);
  font-family: 'Segoe UI', sans-serif;
}

.custom-slide .left,
.custom-slide .right {
  width: 48%;
}

.custom-slide h2 {
  color: #1a5276;
  margin-bottom: 0.5em;
}

.custom-slide ul {
  list-style-type: disc;
  padding-left: 1.2em;
  color: #2e4053;
}

.custom-slide img {
  width: 100%;
  border: 2px solid #ccc;
  border-radius: 8px;
}
</style>

# Beispiel-Präsentation mit HTML-Custom-Slide

---

## Normale LiaScript-Folie

Das hier ist eine Standard-Folie mit Markdown-Elementen.

---

:: HTML Folie

<div class="custom-slide">
  <div class="left">
    <h2>Inhalt links</h2>
    <ul>
      <li>Vorteil A</li>
      <li>Vorteil B</li>
      <li>Vorteil C</li>
    </ul>
  </div>
  <div class="right">
    <h2>Illustration</h2>
    <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/4/4f/Iconic_image_of_Earth_from_space.jpg/800px-Iconic_image_of_Earth_from_space.jpg" alt="Bild">
  </div>
</div>

::

---

## Fazit

Auch vollständig selbstgestaltete Folien sind in LiaScript möglich – du brauchst nur HTML & CSS direkt im Markdown.
