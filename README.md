# WKB for VBA, prueba de concepto.

Prueba de concepto para comprobar la viavilidad de implementar un parser de WKB en VBA.

La implementacion se ha desarrollado en Linux usando Gambas3. Para portarlo a VBA deberia modificarse el metodo estatico **Create** de **Utils.ByteBuffer** para que use la clase **ByteBuffer_vba** en lugar de **ByteBuffer_gb**, y modificar la clase **ByteBuffer_vba**, descomentarizando el codigo de esta.





