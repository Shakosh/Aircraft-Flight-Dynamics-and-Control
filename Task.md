`Task:` For your exam2 airplane, you are to design a pitch-rate tracking CAS to meet certain specifications. The specifications below provide maximum allowable elevator deflection (from its equilibrium value) and settling time for a command of 1 deg/sec pitch-rate. Below are suggested target values on short-period modes only as a ‘help’ – you don’t have to meet these.
- max elevator deflection: 2 deg
- settling time: 5 sec
- short-period mode damping ratio: 0.7
- short-period mode damped frequency: 5.8 rad/sec

`Hardware:` 
- an angle-of-attack (AoA) sensor, along with a filter with transfer function 10/(s+10)
- a pure (no need for filter) pitch-rate sensor
- actuator motor with transfer function 20.2/(s+20.2)

`Method:` Use the short-period approximation to design the CAS with $\alpha$ and *q* feedback. Verification: Demonstrate the success of your design by using appropriate plots, still using the short-period approximation.

`Evaluation:` In lieu of evaluating your CAS with the actual airplane, use the full longitudinal model (in place of the short-period approximation) to evaluate your design. 