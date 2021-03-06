
### Bongard-Logo Dataset

### Introduction

These are the Python scripts used for generating the Bongard-Logo dataset. The Bongard-Logo dataset consists of three types of Bongard problems, freeform, basic, and abstract. For more details about the design and instructions on these three types of Bongard problems, please read the Bongard-Logo dataset documentation.


#### Freeform

![Freeform](demo/ff/ff_nact2_5_0107.png)


#### Basic

![Basic](demo/bd/bd_inverse_asymmetric_house-square_dagger2_0000.png)

#### Abstract

![Abstract](demo/hd/hd_symmetric-unbalanced_two_0014.png)

### Usages


To generate the dataset, please run the following command in the terminal.

```bash
python run.py
```

Once the generation is complete, there should be 3600 freeform problems, 4000 basic problems, and 4400 abstract problems.

```
$ ls images/ff/png/ | wc -l
3600
$ ls images/bd/png/ | wc -l
4000
$ ls images/hd/png/ | wc -l
4400
```

The action programs for each type of the problems are saved as `ff_action_program`, `bd_action_program.json`, `hd_action_program.json`, respectively, in each directory.



### References



