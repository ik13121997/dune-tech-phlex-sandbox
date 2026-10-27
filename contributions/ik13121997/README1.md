#Pratima: my first Phlex workflow



## What this does
20 spills & writes only the `sum` product with FORM."

## How to run it

phlex -c ../dune-tech-phlex-sandbox/contributions/ik13121997/my-workflow.jsonnet --stage ik13121997

few lines from o/p

=== form_output_module::save_data_products ===
Creator: numbers_source:provide_i
Stage: ik13121997
Data cell: [spill:20]
Number of products: 1
  Product: input/i
Wrote 1 products to FORM

=== form_output_module::save_data_products ===
Creator: add_cpp:add
Stage: ik13121997
Data cell: [spill:20]
Number of products: 1
  Product: add_cpp:add/sum
Wrote 1 products to FORM
[2026-10-27 11:24:04.640] [info] 

Seen layers:

  job
   │ 
   └ spill: 20

[2026-10-27 11:24:04.640] [info] CPU time: 0.38887s  Real time: 0.43823s  CPU efficiency:  88.74%
[2026-10-27 11:24:04.640] [info] Max. RSS: 302.080 MB
Apptainer> pwd

## One thing I learned today

Using pull request and registering on PHLEX 



<Anything: a git command, a Phlex word, a mistake you made and fixed.>

cmake --build . >> i forgot the dot

#One word for today

learnt something new
