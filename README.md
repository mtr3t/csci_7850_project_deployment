# Transfer Reinforcement Learning within a Partially Observable Environment with Input-Gated and Output-Gated Working Memory

## Purpose:

This project explores input and output gated working memory and the effects it has on transfer learning. The project is still currently being developed.

## TL;DR:

To run this code you will need Jupyter Notebook installed along with TensorFlow.

1. Open a terminal.

2. Copy and paste this command:

```
git clone https://github.com/mtr3t/csci_7850_project_deployment.git
```

3. To run the pre-trained model:

With Jupyter Notebook open:

```
i_maze_input_gate_output_gate_final_code_red_greed_purple_load.ipynb
```

Run the notebook line by line for more suspence!

4. To train a model:

with jupyter notebook open:

```
i_maze_input_gate_output_gate_final_code_red_greed_purple.ipynb
```

run the notebook

The current code is set for saving network weights and hrr memory. To change this behavior please change:

```
import hrr_persistant_memory as hrr
```
to

```
import hrr as hrr
```

This will allow you to run the model without creating memory files.

5. enjoy

If you have any questions or want to hang out email me mtr3t@mtmail.mtsu.edu

Feel free to make the code better!

# Contributors

Matthew Radice (MTSU - mtr3t@mtmail.mtsu.edu)

Joshua L. Phillips (MTSU - Joshua.Phillips@mtsu.edu)
