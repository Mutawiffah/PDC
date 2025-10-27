# PDC Exam Project – Image Watermarking using Parallel and Distributed Processing

This repository contains all four tasks of the PDC (Parallel and Distributed Computing) exam.

## Tasks Overview
| Task | Description |
|------|--------------|
| Task 1 | Sequential image watermarking |
| Task 2 | Parallel watermarking using multiprocessing |
| Task 3 | Simulated distributed processing using Manager() |
| Task 4 | Performance report and analysis |

## Results Summary
| Method | Best Configuration | Time (s) | Speedup |
|--------|--------------------|----------|----------|
| Sequential | Single Process | 0.29 | ---- |
| Parallel | 4 Workers | 0.35 | 1.89x |
| Distributed | 2 Simulated Nodes | 0.070 | **2.83x (Best Overall Performance)** |

## Discussion
The distributed simulation achieved the best overall efficiency with a 2.83x speedup.
It efficiently divided the dataset across two logical nodes, minimizing overhead and
optimizing CPU usage on a single system.

## Requirements
- Python 3
- Jupyter Notebook or Google Colab
- Pillow (PIL)
- multiprocessing

## Files
- `Sequential_Process.ipynb`
- `Parallel_Process.ipynb`
- `Distributed_Simulation.ipynb`
- `report.txt`

## How to Run
1. Upload all zip datasets (`cats.zip`, `dogs.zip`, `cars.zip`, `flowers.zip`) in Colab.
2. Run each notebook sequentially.
3. Check printed processing times and saved outputs.

## Output Folders
- `output_seq/` — Sequential results  
- `output_parallel/` — Parallel results  
- `output_distributed/` — Distributed results  

## Author
Mutawiffah Mudassar Khan
