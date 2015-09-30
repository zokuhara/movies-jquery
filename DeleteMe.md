$("#button").on("click", function (){
  $("#low-budgets").html("");
  $("#leo-movies").html("");
})




  var leoMovies = _.where(movies, {star: "Leonardo DiCaprio"})
