# Clase
Array3D=[[[0 for x in range (4)]0 for x in range (3)]0 for x in range (2)]
print(Array3D)
print("---Grid---")
tab=' '
cont=1
for grid in Array3D:
    print(f"{tab*int(cont-1)}Capa{cont}]")
  for ren in grid:
    print(f"{tab*(cont-1)}{ren}")
  print("")
  cont+=1
  
