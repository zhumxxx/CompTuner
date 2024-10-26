# CompTuner


The CompTuner.py is the code for Compiler Autotuning through Multiple Phase Learning. For example, if you want to use it to tune program correlation, you can input command python CompTuner.py --log_file=correlation_comptuner.log --source_path=/home/user/polybench-code/datamining/correlation --gcc_path=gcc --flag_path=/home/user/flag.txt.

In this command, --log_file is your log file name, --source_path is your program path, --gcc_path is your compiler path, and --flag_path is for your tuning optimization flags. Moreover, if your program has parameters, you need to input --exec_param. 