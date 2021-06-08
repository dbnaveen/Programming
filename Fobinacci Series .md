
    function fibonacci(num) {
        let res = [0, 1];
        for (var i = 2; i < num; i++) {
            var index1 = i - 1;
            var index2 = i - 2;
            var c = res[index1] + res[index2];
            res.push(c);
        }
        console.log(res);
    }

    fibonacci(5); // [0, 1, 1, 2, 3]
