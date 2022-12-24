<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>JS</title>

    <style>
        * {
            padding: 0;
            margin: 0;
            box-sizing: border-box;
        }

        body {
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            font-size: .875rem;
        }

        .box {
            width: 90%;
            margin: 10px auto;
        }

        .box .head {
            font-weight: 700;
            text-align: center;
            font-size: 1.33rem;
            background-color: rgb(15, 14, 14);
            color: white;
            padding: 7px 3px;
            cursor: pointer;
            border: #ccc 1px solid;
            border-top-left-radius: 5px;
            border-top-right-radius: 5px;

        }

        .box .body {
            padding: 3px 3px 7px 3px;
            text-align: justify;
            border: #CCC 1px solid;
            border-bottom-left-radius: .25rem;
            border-top: none;
        }

        .hide {
            display: none;
        }

        .show {
            display: block;
        }
    </style>
</head>

<body>

    <div class="box">
        <div class="head" id="boxhead">
            About Lorem || Javascript toggle
        </div>
        <div class="body" id="boxbody">
            Lorem ipsum dolor sit, amet consectetur adipisicing elit. Quasi dolor provident neque libero delectus maxime
            inventore veniam a amet sed, blanditiis assumenda eligendi! Voluptatem atque quisquam minus, aliquid fugiat
            repudiandae.
            Lorem ipsum dolor sit amet, consectetur adipisicing elit. Earum beatae cupiditate modi repellendus eos
            reiciendis corrupti qui illum magni recusandae cumque ducimus, dignissimos delectus maiores amet, nesciunt
            eveniet nobis voluptate!
            Lorem ipsum dolor sit amet consectetur adipisicing elit. Animi iure neque assumenda error ad pariatur? Earum
            omnis veritatis vel voluptatibus! Velit amet earum hic dolore blanditiis asperiores animi consequuntur
            dolorem?

        </div>
    </div>

    <script>
       
        document.getElementById("boxhead").addEventListener("click", ()=>{

            document.getElementById("boxbody").classList.toggle('hide');
        }, false)


        /*         document.getElementById("boxhead")
                .addEventListener("click", () => {
                    var d = document.getElementById("boxbody");
                    console.log(d);
                    d.classList.toggle('hide');
                }, false);
     */




    </script>

</body>

</html>
