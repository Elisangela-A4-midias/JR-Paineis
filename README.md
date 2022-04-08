To top buttom   https://www.youtube.com/watch?v=ehVS_FQ3PVw  Usado na JR Painéis

JAVASCRIPT

<script src="https://code.jquery.com/jquery-3.6.0.min.js"></script>
<script>
//You can replace offset value from here
var offset = 300
$(window).on('load scroll', function(){
    
    if( $(window).scrollTop() > offset ){
        $('body').addClass('show')
    }else{
        $('body').removeClass('show')
    }
})
</script>


CSS
selector{
    opacity: 0;
    transition: all 0.3s ease-in-out;
}
body.show selector{
    opacity: 1;
}
