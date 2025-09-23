they move as much of their work as possible from the application’s threads to separate GC threads

Running on all the system’s cores, the workload under test is CPU bound, not leaving enough CPU resources for the concurrent GC threads of ZGC