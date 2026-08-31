# motor de ajedrez tuna

autor: dominic fuentes

un motor de ajedrez uci escrito en c++20.

## compilar

cmake --preset release
cmake --build build/release --config release

## ejecutar

./build/release/engine/release/tuna.exe

## uci

uci
isready
position startpos
go depth 15

## licencia

mit (el sondeo fathom syzygy tiene licencia mit, ver engine/third_party/fathom)