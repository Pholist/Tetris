javac -d bin/ -classpath lib/commons-lang3-3.5.jar src/fr/ubo/tetris/*.java
cd bin
jar -cf ./fr/Tetris.jar fr/ubo/tetris/*
java -cp ./fr/Tetris.jar;../lib/commons-lang3-3.5.jar fr.ubo.tetris.Tetris