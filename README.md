# Itemrank Algorithm
 
<!-- PROJECT LOGO -->
<br />
<p align="center">
  <a href="https://github.com/othneildrew/Best-README-Template">
    <img src="logo.png" alt="Logo" width="70" height="70">
  </a>
  <h3 align="center">Itemrank Algorithm</h3>
</p>



<!-- ABOUT THE PROJECT -->
## About The Project
The repository includes the implementation of Itemrank algorithm, defined in this [paper](https://www.aaai.org/Papers/IJCAI/2007/IJCAI07-444.pdf).   
The project was implemented as part of the High Level Synthesis course in the 9th semester of ECE Democritus University of Thrace supervised by Associate professor George Dimitrakopoulos.

The code was optimized in order to achieve the best hardware performance possible.  
This implementation is optimized taking advantage of :
- the heap data structure   
- 128-bit sparse representation 
- loop tilling 
- further catapult optimizations (unroll, pipeline)

<!-- GETTING STARTED -->
## Getting Started
To get started make sure you have installed all the prerequisites in your computer.

### Prerequisites
To compile this implementation of Itemrank you will need the libraries included in the [libraries' folder](https://github.com/emmanouilidisk/HLS_Project/tree/main/libraries) and a C++ compiler.


<!-- CONTRIBUTING -->
## Contributing

Contribute following the above steps:

1. Fork the Project
2. Create your Feature Branch (`git checkout -b new_branch_name`)
3. Commit your Changes (`git commit -m 'Add some extra functionality'`)
4. Push to the Branch (`git push origin new_branch_name`)
5. Open a Pull Request  

