<!DOCTYPE html>
<html lang="pl">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>stonicziczi</title>
</head>
<body>
    <header>
       <h1><p>E EO</p></h1>
    </header>
    <main>
       <h2><p>Tablica: </p><h2>
        <script>
            // let tabela = [];
            // tabela[0] = 'skibidi';
            // tabela[1] = 2115;
            // tabela[2] = 5662;
            // document.write(tabela);
            // document.write(`<p>Zawartość tablic: ${tabela.pop()} </p>`);
            // document.write(`<p>Zawartość tablic: ${tabela.unshift("essa")} </p>`);
            // document.write(`<p>Zawartość tablic: ${tabela.pop()} </p>`);    
            // document.write(`<p>Zawartość tablic: ${tabela} </p>`);


            // let tabelaLicz = [1,2,3,4,5,6,7,8,9,10];
            // let tabela2 = [];
            // while (tabelaLicz.length){
            //     tabela2[tabela2.length] = tabelaLicz.pop();
            // }
            // document.write(tabela2);
            // document.write(tabelaLicz);

            let skibidi = [];
            let skibidi2 = [];
            let skibidi3 = [];

            for(let i=100;i < 200;i++)
                if(i%2==0){
                skibidi[i] = i;
            }

            for(let i=100;i < 200;i++)
                if(i%2!=0){
                skibidi2[i] = i;
            }


            for(let i=0;i < skibidi2.length+skibidi.length;i++){
                skibidi3[i] = i
            }
            document.write(skibidi3);


        </script>
    </main>
</body>
</html>
