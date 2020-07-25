# remove module-info.class from a XYZ.jar
1. make dir XYZ and move XYZ.jar in that and go to XYZ dir from cmd
2. jar xvf XYZ.jar
3. remove module-info.class
4. may rename old XYZ.jar to XYZ_OLD.jar and move out from the dir
5. jar cvf XYZ.jar .
6. move new XYZ.jar at original location 
7. delete dir XYZ 
