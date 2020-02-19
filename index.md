<button name="button" onclick="addThesesFrSearch()">Ajouter le moteur de recherche theses.fr</button>
<button name="button" onclick="addStarSearch()">Ajouter le moteur de recherche star.theses.fr</button>
<button name="button" onclick="addStepSearch()">Ajouter le moteur de recherche step.theses.fr</button>

<script>
  function addThesesFrSearch() { 
    window.external.AddSearchProvider("https://raw.githubusercontent.com/Eonm/theses-fr-search/master/theses-fr-search.xml");
  }; 
  
  function addStarSearch() { 
    window.external.AddSearchProvider("https://raw.githubusercontent.com/Eonm/theses-fr-search/master/star-search.xml");
  };
  
  function addStepSearch() { 
    window.external.AddSearchProvider("https://raw.githubusercontent.com/Eonm/theses-fr-search/master/step-search.xml");
  };
</script>

