
<body>
    <img class="my-foto" src="/images/image1-small.jpg"  data-large="/images/image1-big.jpg" title="Фото1">
    <img class="my-foto" src="/images/image2-small.jpg"  data-large="/images/image2-big.jpg" title="Фото2">
    <img class="my-foto" src="/images/image3-small.jpg"  data-large="/images/image3-big.jpg" title="Фото3">

    <script src="https://cdnjs.cloudflare.com/ajax/libs/jquery/3.4.0/jquery.min.js></script>
    <script src="zoomsl.js"></script>

    <script>
        $(document).ready(function () {
            $(".my-foto").imagezoomsl();
        });
    </script>
</body>
```
