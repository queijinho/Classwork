<html>
    <script>
        var numberPrimo = "";
        function numeroPrimo(primo){
            if(primo == 2){
                numberPrimo = "O número " + primo + " é primo";
            }else if(primo == 3){
                numberPrimo = "O número " + primo + " é primo";
            }else{
                if(primo/1 && primo/primo){
                    if(primo % 2 === 0){
                        numberPrimo = "O número " + primo + " não é primo";
                    }else if(primo % 3 === 0){
                        numberPrimo = "O número " + primo + " não é primo";
                    }else if(primo % 13 === 0){
                        numberPrimo = "O número " + primo + " não é primo";
                    }else{
                        numberPrimo = "O número " + primo + " é primo";
                    }
                }
            }
            return numberPrimo;
        }
    </script>
</html>
