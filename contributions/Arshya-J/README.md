# Arshya-J: my first Phlex workflow



**Who I am:** <Arshya-J, IISc Bangalore, Neutrino Oscillations>

## What this does

Runs the python example workflow on 20 spills
spill: { parent: 'job', total: 20, starting_number: 3 }

## How to run it

cd ~/phlex-work/build-sandbox
phlex -c ../dune-tech-phlex-sandbox/contributions/Arshya-J/my-workflow.jsonnet --stage Arshya-J

## What you should see

Seen layers:

  job
   │ 
   └ spill: 20

## One thing I learned today

a Phlex word

## One word for today

Broadened my horizon
