# AOC2
## TRABALHO 1 DE AOC2

### COMANDOS NO SIMPLESCALAR

#### Vortex_1 experimento 1:
- direto</br>`$ ./sim-cache -cache:il1 il1:256:32:1:l -cache:dl1 dl1:256:32:1:l -cache:il2 none -cache:dl2 none -tlb:itlb none -tlb:dtlb none vortex.ss vortex.in `
- 2-way</br>`$./sim-cache -cache:il1 il1:128:32:2:l -cache:dl1 dl1:128:32:2:l -cache:il2 none -cache:dl2 none -tlb:itlb none -tlb:dtlb none vortex.ss vortex.in `
- 4-way</br>`$./sim-cache -cache:il1 il1:64:32:4:l -cache:dl1 dl1:64:32:4:l -cache:il2 none -cache:dl2 none -tlb:itlb none -tlb:dtlb none vortex.ss vortex.in `
- total assoc.</br>`$./sim-cache -cache:il1 il1:1:32:256:l -cache:dl1 dl1:1:32:256:l -cache:il2 none -cache:dl2 none -tlb:itlb none -tlb:dtlb none vortex.ss vortex.in `

#### I_Jpeg experimento 1:
- direto</br>`$./sim-cache -cache:il1 il1:256:32:1:l -cache:dl1 dl1:256:32:1:l -cache:il2 none -cache:dl2 none -tlb:itlb none -tlb:dtlb none ijpeg.ss -image_file tinyrose.ppm -compression.quality 90 -compression.optimize_coding 0 -compression.smoothing_factor 90 -difference.image 1 -difference.x_stride 10 -difference.y_stride 10 -verbose 1 -GO.findoptcomp `
- 2-way</br>`$./sim-cache -cache:il1 il1:128:32:2:l -cache:dl1 dl1:128:32:2:l -cache:il2 none -cache:dl2 none -tlb:itlb none -tlb:dtlb none ijpeg.ss -image_file tinyrose.ppm -compression.quality 90 -compression.optimize_coding 0 -compression.smoothing_factor 90 -difference.image 1 -difference.x_stride 10 -difference.y_stride 10 -verbose 1 -GO.findoptcomp `
- 4-way</br>`$./sim-cache -cache:il1 il1:64:32:4:l -cache:dl1 dl1:64:32:4:l -cache:il2 none -cache:dl2 none -tlb:itlb none -tlb:dtlb none ijpeg.ss -image_file tinyrose.ppm -compression.quality 90 -compression.optimize_coding 0 -compression.smoothing_factor 90 -difference.image 1 -difference.x_stride 10 -difference.y_stride 10 -verbose 1 -GO.findoptcomp `
- total assoc.</br>`$./sim-cache -cache:il1 il1:1:32:256:l -cache:dl1 dl1:1:32:256:l -cache:il2 none -cache:dl2 none -tlb:itlb none -tlb:dtlb none ijpeg.ss -image_file tinyrose.ppm -compression.quality 90 -compression.optimize_coding 0 -compression.smoothing_factor 90 -difference.image 1 -difference.x_stride 10 -difference.y_stride 10 -verbose 1 -GO.findoptcomp `

#### Vortex_1 experimento 2:
- LRU</br>`$./sim-cache -cache:il1 il1:1:32:256:l -cache:dl1 dl1:1:32:256:l -cache:il2 none -cache:dl2 none -tlb:itlb none -tlb:dtlb none vortex.ss vortex.in `
- FIFO</br>`$./sim-cache -cache:il1 il1:1:32:256:f -cache:dl1 dl1:1:32:256:f -cache:il2 none -cache:dl2 none -tlb:itlb none -tlb:dtlb none vortex.ss vortex.in `
- RANDOM</br>`$./sim-cache -cache:il1 il1:1:32:256:r -cache:dl1 dl1:1:32:256:r -cache:il2 none -cache:dl2 none -tlb:itlb none -tlb:dtlb none vortex.ss vortex.in `

#### I_Jpeg experimento 2:
- LRU</br>`$./sim-cache -cache:il1 il1:1:32:256:l -cache:dl1 dl1:1:32:256:l -cache:il2 none -cache:dl2 none -tlb:itlb none -tlb:dtlb none ijpeg.ss -image_file tinyrose.ppm -compression.quality 90 -compression.optimize_coding 0 -compression.smoothing_factor 90 -difference.image 1 -difference.x_stride 10 -difference.y_stride 10 -verbose 1 -GO.findoptcomp `
- FIFO</br>`$./sim-cache -cache:il1 il1:1:32:256:f -cache:dl1 dl1:1:32:256:f -cache:il2 none -cache:dl2 none -tlb:itlb none -tlb:dtlb none ijpeg.ss -image_file tinyrose.ppm -compression.quality 90 -compression.optimize_coding 0 -compression.smoothing_factor 90 -difference.image 1 -difference.x_stride 10 -difference.y_stride 10 -verbose 1 -GO.findoptcomp `
- RANDOM</br>`$./sim-cache -cache:il1 il1:1:32:256:r -cache:dl1 dl1:1:32:256:r -cache:il2 none -cache:dl2 none -tlb:itlb none -tlb:dtlb none ijpeg.ss -image_file tinyrose.ppm -compression.quality 90 -compression.optimize_coding 0 -compression.smoothing_factor 90 -difference.image 1 -difference.x_stride 10 -difference.y_stride 10 -verbose 1 -GO.findoptcomp `
