# Results from experiments on the language segmentation task

## Setup

Before trying to run anything, please execute in the terminal the following to download some large files (model checkpoints, activation_with_input.pt, etc.):

```git lfs pull```

## Data

activation_with_input.pt is a dictionary saved with torch.save and has the following items:

- input - input image to the 'scratch'
- scratch.head1 - activation of the scratch.head1 module (see lang_seg_full_architecture.txt)
- scratch.output_conv - analogous to scratch.head1
  