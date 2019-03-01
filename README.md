# neg_silk.ulp
Eagle CAD ULP script to generate negative silk screen in one step. The orginal 'negasilk.ulp' ULP process all polygons (converting them to silkscreen). So you need to delete the unwanted shapes produced from the other functional polygons before runing this ULP or to run it in blank .brd file. Also this ULP generates a script file to be executed to finish ULP’s work.

This one can generate the negative silkscreen even with exestance of other polygons by naming the negative one with NEG_SILK and also group the output (in tplace ouput) to be moved easily to any place in PCB.

How to use neg_silk.ulp: https://atadiat.com/en/e-negative-silkscreen-eagle-ulp/
How to use orginal negasilk.ulp: http://www.electronics-lab.com/create-inverted-silkscreen-cadsoft-eagle/ 

Improtant note: This ULP is test on Eagle V7.x and Eagle V9.3 ... For some reason, the new Eagle CAD team (after Autodesk acquisition) has changed something in ULP, So the ULP enters a stange loop in some V8.x versions and work very good with V9.3.

