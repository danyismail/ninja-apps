$(document).ready(function () {
    var _url = "https://my-json-server.typicode.com/danyismail/pwadb/ninja"

    var dataResult = ''

    $.get(_url, function(data) {
        $.each(data, function(key, items){
          console.log(data)
          dataResult += "<div class='card ml-2 mr-2' style='width: 15rem;'>" +  items.abilty  + "<img src=" + items.avatar + "<img>" 
          + "<div class='divider'></div>"
          + "<a href='#' class='btn btn-info btn-xs'>" + items.ninja_name + "</a>"
          +"</div>" 
        })

        $('#api').html(dataResult)
    })

})
//end document of jquery