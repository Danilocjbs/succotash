# succotash
<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>

<body>
    <script>
        const instrumentos = [];

        //console.log(instrumentos);

        instrumentos.push('guitarra');
        instrumentos.push('baterria');
        instrumentos.push('Ocarina');

        console.log(instrumentos);
        instrumentos.forEach(instrumentos, i =>{
            console.log(i, instrumentos);
        });

    
        const instrumentosComB = instrumentos.filter((instrumento, i) =>{
            return instrumento [0]== 'B';
        })
        instrumentos.reverse();
        
        instrumentos.forEach(instrumento,i => {
            console.log(i,instrumento);
        })
    const indecedebateria = instrumentos.indexOf('Banjo')
        cosole.log(indecedebateria);

const instrumentosComTraco = instrumentos.join(' _');

console.log(instrumentosComTraco);
   </script>
</body>

</html>
