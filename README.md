### RoboCup Logistics Leauge (RCLL) Simulation Chart
This repository contains a helm chart for the RCLL that allow one to run the simulation inside a kubernetes cluster.

Add Helm Repository
`helm repo add rcll https://pkohout.github.io/rcll-simulation-chart/`

Install Release
`helm upgrade --install --create-namespace --namespace rcll-test rcll-simulation rcll/rcll-simulation`