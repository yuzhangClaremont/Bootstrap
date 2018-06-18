# Bootstrap
https://www.youtube.com/watch?v=qIULMnbH2-o&list=PL6gx4Cwl9DGBPw1sFodruZUPheWVKchlM

Bootstrap CDN
starter code
```
<!DOCTYPE html>
<html lang="en">
    <head>
    <title>Utopian</title>
        <meta charset="utf-8">
        <!-- user screen, use device scren, dont zoomin or out -->
        <meta name="viewport" content="width=device-width, initial-scale=1">
        <link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.1.1/css/bootstrap.min.css" integrity="sha384-WskhaSGFgHYWDcbwN70/dfYBj47jz9qbsMId/iRN3ewGhXQFZCSftd1LZCfmhktB" crossorigin="anonymous">
      
        <script src="https://code.jquery.com/jquery-3.3.1.slim.min.js" integrity="sha384-q8i/X+965DzO0rT7abK41JStQIAqVgRVzpbzo5smXKp4YfRvH+8abtTE1Pi6jizo" crossorigin="anonymous"></script>
        <script src="https://cdnjs.cloudflare.com/ajax/libs/popper.js/1.14.3/umd/popper.min.js" integrity="sha384-ZMP7rVo3mIykV+2+9J3UJ46jBk0WLaUAdn689aCwoqbBJiSnjAK/l8WvCWPIPm49" crossorigin="anonymous"></script>
        <script src="https://stackpath.bootstrapcdn.com/bootstrap/4.1.1/js/bootstrap.min.js" integrity="sha384-smHYKdLADwkXOn1EmN1qk/HfnUcbVRZyYmZ4qpPea6sjB/pTJ0euyQp0Mk8ck+5T" crossorigin="anonymous"></script>
    </head>
    
</html>
```

## container

to fix size, use container class
```
    <body>
        <div class="container">
            <h1>Welcome to Utopian Rainbow</h1>
            <p>Together we define a better tomorrow!</p>
        </div>
    </body>
```

to use full screen, use container-fluid class
```
        <div class="container">
            <h1>Welcome to Utopian Rainbow</h1>
            <p>Together we define a better tomorrow!</p>

        </div>
```

## grid layout
12 columns

xs: phone
sm: tablets
md: desktop labtop
lg: larger desktop

```
    <div class="row">
        <!-- 3*4 = 12 in total -->
        <div class="col-md-4" style="background-color: #FF9999">LEFT </div>
        <div class="col-md-4" style="background-color: rgb(153, 209, 255)">MIDDLE </div>
        <div class="col-md-4" style="background-color: rgb(247, 153, 255)">RIGHT </div>
    </div>
```

## text manimulations

### highlight
mark tag
```
<p>You can <mark>highlight </mark> text here.</p>
```

### quote
```
            <blockquote class="blockquote text-center">
                <p>You can also use quote here</p>
                <footer class="blockquote-footer">Author </footer>
            </blockquote>
```

### lists

```
            <h4>Thins to do when bored</h4>
            <dl>
                <dt>indoors</dt>
                    <dd>-take a nap</dd>
                    <dd>-Netflix</dd>
                <dt>outdoors</dt>
                    <dd>-surfing</dd>
            </dl>
```

### code tag and pre tag for code
```
            <p>you can also put <code>source code </code> here for single line code</p>
            <p>for multiline code you can use pre tag</p>
            <pre>
                for i in list:
                    print i
            </pre>
```