

<!DOCTYPE HTML>
<html class="no-js" lang="en-GB">
<head>
    <meta charset="UTF-8" />
    <meta http-equiv="Content-Type" content="text/html; charset=utf-8" />
    <meta http-equiv="X-UA-Compatible" content="IE=edge,chrome=1" />
    <title>A completely gutted page</title>

    <link rel='dns-prefetch' href='//ajax.googleapis.com' />
    <link rel='dns-prefetch' href='//code.jquery.com' />
    <link rel='dns-prefetch' href='//use.fontawesome.com' />
    <link rel='dns-prefetch' href='//fonts.googleapis.com' />
    <link rel='dns-prefetch' href='//use.typekit.net' />
    <link rel='dns-prefetch' href='//s.w.org' />
    <script src="https://use.fontawesome.com/916b091307.js"></script>
    <link rel='stylesheet' id='google_font-css'  href='https://fonts.googleapis.com/css2?family=Montserrat%3Aital%2Cwght%400%2C400%3B0%2C700%3B1%2C400%3B1%2C700&#038;display=swap' type='text/css' media='all' />
<!--    <script src="//cdnjs.cloudflare.com/ajax/libs/jquery/3.2.1/jquery.min.js"></script>-->

<!--    BOOTSTRAP-->
    <!-- CSS only -->
    <link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/css/bootstrap.min.css" integrity="sha384-JcKb8q3iqJ61gNV9KGb8thSsNjpSL0n8PARn9HuZOnIxN0hoP+VmmDGMN5t9UJ0Z" crossorigin="anonymous">

    <!-- JS, Popper.js, and jQuery -->
    <script src="https://code.jquery.com/jquery-3.5.1.slim.min.js" integrity="sha384-DfXdz2htPH0lsSSs5nCTpuj/zy4C+OGpamoFVy38MVBnE+IbbVYUew+OrCXaRkfj" crossorigin="anonymous"></script>
    <script src="https://cdn.jsdelivr.net/npm/popper.js@1.16.1/dist/umd/popper.min.js" integrity="sha384-9/reFTGAW83EW2RDu2S0VKaIzap3H66lZH81PoYlFhbGU+6BZp6G7niu735Sk7lN" crossorigin="anonymous"></script>
    <script src="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/js/bootstrap.min.js" integrity="sha384-B4gt1jrGC7Jh4AgTPSdUtOBvfO8shuf57BaghqFfPlYxofvL8/KUEfYiJOMMV+rV" crossorigin="anonymous"></script>

    <link rel='stylesheet' href='custom.css' type='text/css' media='all' />

</head>

<body class="home page-template page-template-templates page-template-page-home page-template-templatespage-home-php page page-id-2 desktop chrome not-ie windows">

<section class="split-banner container">
    <div class="row">
        <div class="intro-text col">
            <h1>Left side header</h1>
            <p>Text description</p>
        </div>

        <div class="interactive-map col">
            <div class="map-wrapper">
                <div class="map">
                    <img class="map-background" src="https://www.happyplacefestival.com/wp-content/uploads/map-outline-with-donation.png" srcset="https://www.happyplacefestival.com/wp-content/uploads/map-outline-with-donation.png 2000w, https://www.happyplacefestival.com/wp-content/uploads/map-outline-with-donation-1364x1536.png 1364w, https://www.happyplacefestival.com/wp-content/uploads/map-outline-with-donation-1818x2048.png 1818w, https://www.happyplacefestival.com/wp-content/uploads/map-outline-with-donation-1704x1920.png 1704w, https://www.happyplacefestival.com/wp-content/uploads/map-outline-with-donation-1243x1400.png 1243w, https://www.happyplacefestival.com/wp-content/uploads/map-outline-with-donation-1065x1200.png 1065w, https://www.happyplacefestival.com/wp-content/uploads/map-outline-with-donation-682x768.png 682w, https://www.happyplacefestival.com/wp-content/uploads/map-outline-with-donation-456x514.png 456w, https://www.happyplacefestival.com/wp-content/uploads/map-outline-with-donation-284x320.png 284w" sizes="( max-width: 2400px ) 100vw, 2400px" alt="" />
                    <div class="map-markers">
                        <div class="marker show" data-id="1" style="top: 50px; left: 50px;">

                            <span class="circle-pulse intro-banner-vdo-play-btn blueCircle" onclick="showModal(this.parentElement.getElementsByClassName('modal-content')[0])">
                                <span class="ripple blueCircle"></span>
                                <span class="ripple blueCircle"></span>
                                <span class="ripple blueCircle"></span>
                            </span>

                            <div class='modal-content hide-modal'>
                                <span class="close" onclick="hideModal(this.parentElement)">&times;</span>
                                <h3>Main Event</h3>
                                <p>Something big that is happening. Link goes to google for demo purposes.</p>
                                <a class="btn btn-outline-primary" role="button" href="https://www.google.com" target="_blank">Enter</a>
                            </div>

                        </div>

                        <div class="marker show" data-id="2"  style="top: 250px; left: 250px;">

                            <span class="circle-pulse intro-banner-vdo-play-btn blueCircle" onclick="showModal(this.parentElement.getElementsByClassName('modal-content')[0])">
                                <span class="ripple blueCircle"></span>
                                <span class="ripple blueCircle"></span>
                                <span class="ripple blueCircle"></span>
                            </span>

                            <div class='modal-content hide-modal'>
                                <span class="close" onclick="hideModal(this.parentElement)">&times;</span>
                                <h3>Secondary Event</h3>
                                <p>To make sure nothing breaks with multiple.</p>
                                <a class="btn btn-outline-primary" role="button" href="https://www.w3schools.com" target="_blank">Enter</a>
                            </div>

                        </div>
                    </div>
                </div>
            </div>
        </div>
    </div>
</section>


<script type='text/javascript' src='https://ajax.googleapis.com/ajax/libs/jquery/3.4.1/jquery.min.js'></script>
<script type='text/javascript' src='https://code.jquery.com/ui/1.12.1/jquery-ui.min.js'></script>
</body>

<script>

    function showModal(source){
        source.classList.remove('hide-modal');
        source.classList.add('show-modal');
    }

    function hideModal(source){
        source.classList.remove('show-modal');
        source.classList.add('hide-modal');
    }

</script>
</html>