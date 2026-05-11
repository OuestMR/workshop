---
layout: page
title: Registration
permalink: /registration/
---
<form>

<label for="nom"><strong>Nom</strong></label><br>
<input type="text" id="nom" name="nom" style="width:300px;"><br><br>

<label for="prenom"><strong>Prénom</strong></label><br>
<input type="text" id="prenom" name="prenom" style="width:300px;"><br><br>

<label for="unite"><strong>Unité de recherche</strong></label><br>
<select id="unite" name="unite" style="width:300px;">
  <option value="">-- Choisir --</option>
  <option value="bio">Biologie</option>
  <option value="info">Informatique</option>
  <option value="math">Mathématiques</option>
</select><br><br>

<label for="email"><strong>Adresse mail</strong></label><br>
<input type="email" id="email" name="email" style="width:300px;"><br><br>

<label for="resume"><strong>Résumé de vos travaux</strong></label><br>
<textarea id="resume" name="resume" rows="6" cols="50"></textarea><br><br>

<button type="submit">Envoyer</button>

</form>
