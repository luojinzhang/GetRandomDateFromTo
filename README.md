# GetRandomDateFromTo
[JS] Get random date from defined date until now and convert them to long

        function random_Date()
        {
            var maxDate = Date.now();
            var minDate = Date.parse('1/1/2017');
            var randomDate = Math.floor(Math.random() * (maxDate - minDate) + minDate);
            return randomDate.toString();
        }
