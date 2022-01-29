# rust-poker
Paul Senzee's perfect hash poker hand evaluator. Ported to Rust by me.

Compile with 

    rustc -C overflow-checks=off poker.rs

You need to turn off overflow checks, since the algorithm acts on bits and the logic is built so that the integer overflow is the way to generate a perfect hash.

Original post by author of the perfect hashing algorithm: http://senzee.blogspot.com/2006/06/some-perfect-hash.html
The implementation is by Cactus Kev here (written in C): https://suffe.cool/poker/code/
