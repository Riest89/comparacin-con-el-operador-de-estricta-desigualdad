# comparacin-con-el-operador-de-estricta-desigualdad
// Configuración
function testStrictNotEqual(val) {
  if (val !== 17) { // Cambia esta línea
    return "Not Equal";
  }
  return "Equal";
}

testStrictNotEqual(10);
