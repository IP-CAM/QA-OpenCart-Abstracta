# 🐞 Bug Report – Error de validación de datos en Last Name al registrarme

- **ID**: BUG-TC-008
- **Título**: Registro con "Last Name" inválido (caracteres númericos en vez de letras)
- **Fecha**: 2025-07-29
- **Criticidad**: Baja
- **Tipo de defecto**: Validación de datos
- **Pasos para reproducir**:
  1. Ingresar a la página de registro.
  2. Completar todos los campos con datos válidos, excepto el campo "Last Name" donde se debe ingresar carácteres numericos (ej: "00000").
  3. Aceptar los términos y condiciones.
  4. Hacer clic en el botón "continue".
- **Resultado esperado**: El sistema debería validar que el campo "Last Name" contenga únicamente caracteres alfabéticos y mostrar un mensaje de error si se ingresan números.
- **Resultado real**: El sistema te redirije a la sección account donde indica que el registro fue un éxito.
- **Evidencia**: ![captura](../evidencias/captura-registro-exitoso.png)
