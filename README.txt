We used Ubuntu 16.04 and Virtual Box 6.0.18
We need versions prior to Spectre Attack was discovered. Later versiosna re all patched. Aand this code wont execute
To compile the programs we need to add march= native
to let the gcc compiler to compile based on host cpu

CacheTime.c demonstrates the time for 'hot' and 'cold' read

FlushReload.c demonstrates if we can access the ssecret read even after memory is flushed
 SpectreExperiment.c is a demo of  Out of order execution
SpectreAttack.c is a demo of the actual spectre attack
SpectreAttackImproved.c is a demo for improving accuracy of teh attack by running it 1000 times
