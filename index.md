<button name="button" onclick="addThesesFrSearch()">Ajouter le moteur de recherche theses.fr</button>
<button name="button" onclick="addStarSearch()">Ajouter le moteur de recherche star.theses.fr</button>

<script>
  function addThesesFrSearch() { 
    window.external.AddSearchProvider("https://raw.githubusercontent.com/Eonm/theses-fr-search/master/theses-fr-search.xml");
  }; 
  
  function addStarSearch() { 
    window.external.AddSearchProvider("https://raw.githubusercontent.com/Eonm/theses-fr-search/master/star-search.xml");
  };
</script>

