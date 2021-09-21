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

#### Vortex_1 experimento 3:
- N</br> `$./sim-cache -cache:il1 il1:256:16:1:l -cache:dl1 dl1:256:16:1:l -cache:il2 none -cache:dl2 none -tlb:itlb none -tlb:dtlb none vortex.ss vortex.in `
- 2N</br> `$./sim-cache -cache:il1 il1:128:32:1:l -cache:dl1 dl1:128:32:1:l -cache:il2 none -cache:dl2 none -tlb:itlb none -tlb:dtlb none vortex.ss vortex.in `
- 4N</br> `$./sim-cache -cache:il1 il1:64:64:1:l -cache:dl1 dl1:64:64:1:l -cache:il2 none -cache:dl2 none -tlb:itlb none -tlb:dtlb none vortex.ss vortex.in `
- 8N</br> `$./sim-cache -cache:il1 il1:32:128:1:l -cache:dl1 dl1:32:128:1:l -cache:il2 none -cache:dl2 none -tlb:itlb none -tlb:dtlb none vortex.ss vortex.in `

#### i_jpeg experimento 3:
- N</br> `$./sim-cache -cache:il1 il1:256:16:1:l -cache:dl1 dl1:256:16:1:l -cache:il2 none -cache:dl2 none -tlb:itlb none -tlb:dtlb none ijpeg.ss -image_file tinyrose.ppm -compression.quality 90 -compression.optimize_coding 0 -compression.smoothing_factor 90 -difference.image 1 -difference.x_stride 10 -difference.y_stride 10 -verbose 1 -GO.findoptcomp `
- 2N</br> `$./sim-cache -cache:il1 il1:128:32:1:l -cache:dl1 dl1:128:32:1:l -cache:il2 none -cache:dl2 none -tlb:itlb none -tlb:dtlb none ijpeg.ss -image_file tinyrose.ppm -compression.quality 90 -compression.optimize_coding 0 -compression.smoothing_factor 90 -difference.image 1 -difference.x_stride 10 -difference.y_stride 10 -verbose 1 -GO.findoptcomp `
- 4N</br> `$./sim-cache -cache:il1 il1:64:64:1:l -cache:dl1 dl1:64:64:1:l -cache:il2 none -cache:dl2 none -tlb:itlb none -tlb:dtlb none ijpeg.ss -image_file tinyrose.ppm -compression.quality 90 -compression.optimize_coding 0 -compression.smoothing_factor 90 -difference.image 1 -difference.x_stride 10 -difference.y_stride 10 -verbose 1 -GO.findoptcomp `
- 8N</br> `$./sim-cache -cache:il1 il1:32:128:1:l -cache:dl1 dl1:32:128:1:l -cache:il2 none -cache:dl2 none -tlb:itlb none -tlb:dtlb none ijpeg.ss -image_file tinyrose.ppm -compression.quality 90 -compression.optimize_coding 0 -compression.smoothing_factor 90 -difference.image 1 -difference.x_stride 10 -difference.y_stride 10 -verbose 1 -GO.findoptcomp `

#### Vortex_1 experimento 4:
- Separada</br>`$./sim-cache -cache:il1 il1:256:32:1:l -cache:dl1 dl1:256:32:1:l -cache:il2 none -cache:dl2 none -tlb:itlb none -tlb:dtlb none vortex.ss vortex.in `
- Unificada</br>`$./sim-cache -cache:il1 dl1 -cache:dl1 ul1:512:32:1:l -cache:il2 none -cache:dl2 none -tlb:itlb none -tlb:dtlb none vortex.ss vortex.in `

#### i_jpeg experimento 3:
- Separada</br>`$./sim-cache -cache:il1 il1:256:32:1:l -cache:dl1 dl1:256:32:1:l -cache:il2 none -cache:dl2 none -tlb:itlb none ijpeg.ss -image_file tinyrose.ppm -compression.quality 90 -compression.optimize_coding 0 -compression.smoothing_factor 90 -difference.image 1 -difference.x_stride 10 -difference.y_stride 10 -verbose 1 -GO.findoptcomp `
- Unificada</br>`$./sim-cache -cache:il1 dl1 -cache:dl1 ul1:512:32:1:l -cache:il2 none -cache:dl2 none -tlb:itlb none -tlb:dtlb none ijpeg.ss -image_file tinyrose.ppm -compression.quality 90 -compression.optimize_coding 0 -compression.smoothing_factor 90 -difference.image 1 -difference.x_stride 10 -difference.y_stride 10 -verbose 1 -GO.findoptcomp `

#### Vortex_1 extra:
- Separada</br>`$./sim-cache -cache:il1 il1:256:32:1:l -cache:dl1 dl1:256:32:1:l -cache:il2 il2:512:32:1:l -cache:dl2 dl2:512:32:1:l -tlb:itlb none -tlb:dtlb none vortex.ss vortex.in `
- Unificada</br>`$./sim-cache -cache:il1 il1:256:32:1:l -cache:dl1 dl1:256:32:1:l -cache:il2 dl2 -cache:dl2 ul2:1024:32:1:l -tlb:itlb none -tlb:dtlb none vortex.ss vortex.in `

#### i_jpeg extra:
- Separada</br>`$./sim-cache -cache:il1 il1:256:32:1:l -cache:dl1 dl1:256:32:1:l -cache:il2 il2:512:32:1:l -cache:dl2 dl2:512:32:1:l -tlb:itlb none -tlb:dtlb none ijpeg.ss -image_file tinyrose.ppm -compression.quality 90 -compression.optimize_coding 0 -compression.smoothing_factor 90 -difference.image 1 -difference.x_stride 10 -difference.y_stride 10 -verbose 1 -GO.findoptcomp `
- Unificada</br>`$./sim-cache -cache:il1 il1:256:32:1:l -cache:dl1 dl1:256:32:1:l -cache:il2 dl2 -cache:dl2 ul2:1024:32:1:l -tlb:itlb none -tlb:dtlb none ijpeg.ss -image_file tinyrose.ppm -compression.quality 90 -compression.optimize_coding 0 -compression.smoothing_factor 90 -difference.image 1 -difference.x_stride 10 -difference.y_stride 10 -verbose 1 -GO.findoptcomp `
