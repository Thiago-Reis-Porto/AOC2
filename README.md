# AOC2
##TRABALHO 1 DE AOC2

#####COMANDOS NO SIMPLESCALAR

####Vortex_1 experimento 1:
- direto
`$ ./sim-cache -cache:il1 il1:256:32:1:l -cache:dl1 dl1:256:32:1:l -cache:il2 none -cache:dl2 none -tlb:itlb none -tlb:dtlb none vortex.ss vortex.in `

2-way
./sim-cache -cache:il1 il1:128:32:2:l -cache:dl1 dl1:128:32:2:l -cache:il2 none -cache:dl2 none -tlb:itlb none -tlb:dtlb none vortex.ss vortex.in
4-way
./sim-cache -cache:il1 il1:64:32:4:l -cache:dl1 dl1:64:32:4:l -cache:il2 none -cache:dl2 none -tlb:itlb none -tlb:dtlb none vortex.ss vortex.in
total assoc.
./sim-cache -cache:il1 il1:1:32:256:l -cache:dl1 dl1:1:32:256:l -cache:il2 none -cache:dl2 none -tlb:itlb none -tlb:dtlb none vortex.ss vortex.in

i_jpeg experimento 1:
direto
./sim-cache -cache:il1 il1:256:32:1:l -cache:dl1 dl1:256:32:1:l -cache:il2 none -cache:dl2 none -tlb:itlb none -tlb:dtlb none ijpeg.ss -image_file tinyrose.ppm -compression.quality 90 -compression.optimize_coding 0 -compression.smoothing_factor 90 -difference.image 1 -difference.x_stride 10 -difference.y_stride 10 -verbose 1 -GO.findoptcomp
2-way
./sim-cache -cache:il1 il1:128:32:2:l -cache:dl1 dl1:128:32:2:l -cache:il2 none -cache:dl2 none -tlb:itlb none -tlb:dtlb none ijpeg.ss -image_file tinyrose.ppm -compression.quality 90 -compression.optimize_coding 0 -compression.smoothing_factor 90 -difference.image 1 -difference.x_stride 10 -difference.y_stride 10 -verbose 1 -GO.findoptcomp
4-way
./sim-cache -cache:il1 il1:64:32:4:l -cache:dl1 dl1:64:32:4:l -cache:il2 none -cache:dl2 none -tlb:itlb none -tlb:dtlb none ijpeg.ss -image_file tinyrose.ppm -compression.quality 90 -compression.optimize_coding 0 -compression.smoothing_factor 90 -difference.image 1 -difference.x_stride 10 -difference.y_stride 10 -verbose 1 -GO.findoptcomp
total assoc.
./sim-cache -cache:il1 il1:1:32:256:l -cache:dl1 dl1:1:32:256:l -cache:il2 none -cache:dl2 none -tlb:itlb none -tlb:dtlb none ijpeg.ss -image_file tinyrose.ppm -compression.quality 90 -compression.optimize_coding 0 -compression.smoothing_factor 90 -difference.image 1 -difference.x_stride 10 -difference.y_stride 10 -verbose 1 -GO.findoptcomp
