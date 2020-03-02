Il y'a un arrêt ici.

Au moment de l'execution du `<script>` le dernier element du DOM c'est le `<script>`, parce que le navigateur n'a pas encore traité le reste de la page.

Alors le resultat c'est `1` (element).

```html run height=60
<html>

<body>
  <script>
    alert(document.body.lastChild.nodeType);
  </script>
</body>

</html>
```
