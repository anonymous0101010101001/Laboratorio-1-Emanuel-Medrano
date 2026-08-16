const readline = require("readline");

const rl = readline.createInterface({
    input: process.stdin,
    output: process.stdout
});

rl.question("Ingrese el nombre de la persona: ", function(nombre){

    rl.question("Ingrese la cantidad de días trabajados al mes: ", function(dias){

        rl.question("Ingrese el gasto diario en desayuno: ", function(desayuno){

            rl.question("Ingrese el gasto diario en almuerzo: ", function(almuerzo){

                rl.question("Ingrese el gasto diario en transporte: ", function(transporte){

                    dias = parseInt(dias);
                    desayuno = parseFloat(desayuno);
                    almuerzo = parseFloat(almuerzo);
                    transporte = parseFloat(transporte);

                    let gastoDiario = desayuno + almuerzo + transporte;
                    let gastoMensual = gastoDiario * dias;

                    console.log("\n----- RESULTADOS -----");
                    console.log("Nombre: " + nombre);
                    console.log("Gasto diario: $" + gastoDiario.toFixed(2));
                    console.log("Gasto mensual estimado: $" + gastoMensual.toFixed(2));

                    rl.close();
                });
            });
        });
    });
});
