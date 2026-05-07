# E7 - Introduction to Programming for Scientists and Engineers: Course Summary

## Course Overview
This course introduces programming concepts and techniques specifically tailored for scientists and engineers, using Python as the primary language. The curriculum progresses from basic Python fundamentals to advanced numerical methods, visualization, and simulation techniques.

---

## Week 1: Introduction to Python and Jupyter Notebooks

### Discussion (w01disc)
- **Jupyter Notebook Basics**
  - Edit mode vs. Command mode (Enter/Esc keys)
  - Keyboard shortcuts: A (insert cell above), B (insert cell below), X (cut), C (copy), V (paste), Y (code cell), M (markdown cell)
  - Cell execution: Shift+Enter (run and advance), Ctrl+Enter (run without advancing)
  - Kernel restart: Kernel → Restart Kernel and Run All Cells

- **Python Fundamentals**
  - Basic syntax and variables
  - Functions: packaging code for reuse
  - Random number generation with `random` module

- **Autograding with Otter**
  - Solution cells followed by test cells
  - Gradescope integration
  - Submission process: `grader.export(pdf=False)`

---

## Week 2: Scalar Data Types and Control Flow

### Lab A (w02Alab): Numerical Operations
- **Physics Problems**
  - Phone falling from table: potential energy, kinetic energy, impact velocity
  - Great Pyramid of Giza: volume calculation, scale model dimensions
  - Vibrating rod: displacement formula with exponential damping and oscillation

- **Mathematical Concepts**
  - Unit conversions (SI units)
  - Complex numbers using `cmath` module
  - Euler's formula for complex exponentials
  - Boolean expressions and logical conditions

### Lecture A (w02Alec): Scalar Data Types and Operator Precedence
- Integer and float types
- Scalar arithmetic operations
- Math module functions
- Complex numbers and cmath module
- Boolean logic

### Lab B (w02Blab): if Statements and While Loops
- **Control Structures**
  - Conditional logic with if/elif/else
  - Loop structures with while
  - Break statements for loop termination

- **Applications**
  - Counting prime numbers using helper function `is_prime()`
  - Estimating π using Madhava-Leibniz series
  - Series convergence with tolerance thresholds

### Lecture B (w02Blec): if Statements and While Loops
- Speeding ticket logic examples (nested conditionals)
- Number adding program with user input
- Loop patterns: condition-based vs. break-based

### Discussion (w02disc)
- Debugging examples
- Non-sequential execution issues
- Float comparison pitfalls
- Functions with multiple return values
- Default input parameters
- Positional vs. keyword arguments

---

## Week 3: Collections and Iteration

### Lab A (w03Alab): Collections
- **Dictionary Operations**
  - Calendar availability checker
  - Key existence checking with `in` operator
  - Dictionary methods and iteration

- **List Operations**
  - Loading CSV data with csv module
  - Voting data analysis
  - List slicing and indexing
  - Finding indices with `.index()` method

- **Set Operations**
  - Finding unique elements
  - Set operations for data deduplication

### Lecture A (w03Alec): Collections
- **Sequence Types**
  - Sets: unordered, unique elements
  - Tuples: immutable sequences
  - Lists: mutable sequences
  - Strings: character sequences
  - Dictionaries: key-value mappings

- **Dictionary Example**
  - Country population data
  - Key-value access patterns

### Lab B (w03Blab): For Loops
- **Voting Analysis**
  - Counting votes per voter with dictionaries
  - Finding fraudulent voters (multiple votes)
  - Election winner determination with tie handling
  - Dictionary iteration with `.items()`

- **Restaurant Bill Calculator**
  - Menu dictionary with prices
  - Order processing with zip/enumerate
  - Tip calculation (18%)
  - Dictionary comprehension for bill totals

### Lecture B (w03Blec): For Loops
- Iterating through different collection types
- Dictionary iteration methods: keys, values, items
- Range, enumerate, and zip functions
- Building dictionaries from parallel lists

### Discussion (w03disc): Comprehensions
- **List Comprehensions**
  - Powers of 2 generation
  - Filtering with conditions
  - Finding smallest positive integer without multiples

- **Text Analysis**
  - Word counting and unique word identification
  - Pattern matching (four-letter words)
  - Word length statistics

- **Event Planning**
  - Lot selection based on area requirements
  - Perimeter-to-area ratio calculations
  - Loop vs. comprehension approaches

---

## Week 4: NumPy Arrays

### Lab A (w04Alab): Introduction to NumPy Arrays
- **Vibrating Rod (Continued)**
  - Creating time grids with `np.linspace`
  - Evaluating functions on arrays (vectorization)
  - Coarse vs. fine sampling comparison
  - NumPy functions: `np.exp`, `np.cos`

- **Settling Time Analysis**
  - Energy calculation: E = (1/2)m*x₀²*(ω²-a²)*e^(-2at)
  - Boolean array operations for threshold detection
  - Finding earliest settling time with `np.where` and `np.min`

### Lecture A (w04Alec): NumPy Part 1
- **Array Creation and Operations**
  - Matrix representation with NumPy vs. lists
  - Numerical aggregations: sum, mean, min, max
  - Boolean aggregations: any, all
  - Sorting arrays

- **Array Operations**
  - Element-wise arithmetic
  - Broadcasting rules
  - 2D ⊗ 1D, 2D ⊗ 2D row, 2D ⊗ 2D column broadcasting

### Lab B (w04Blab): Working with NumPy Arrays
- **1D Heat Conduction**
  - Loading CSV data with `np.loadtxt`
  - Temperature unit conversion (Celsius to Fahrenheit)
  - Temporal and spatial averaging
  - Standard deviation calculation without `np.std`

- **Bouncing Ball Simulation**
  - Time array creation with `np.arange`
  - Memory allocation with `np.empty` and `np.full`
  - State update loop with physics modeling
  - Bounce detection and energy dissipation
  - Rolling state tracking

### Lecture B (w04Blec): NumPy Part 2
- **Finding Closest Phone to Tower**
  - Distance calculations with 3D coordinates
  - Boolean masking for distance filtering

- **Indexing Techniques**
  - Integer and slice indexing
  - Integer array indexing
  - Boolean mask indexing

- **Array Creation Methods**
  - `np.arange`: step-based sequences
  - `np.linspace`: evenly-spaced points
  - `np.empty`, `np.zeros`, `np.ones`, `np.full`: pre-allocation

### Discussion (w04disc): Conway's Game of Life
- Cellular automaton simulation
- Grid-based state representation
- Neighbor counting and update rules
- 3D array for time evolution
- Animation with Matplotlib

---

## Week 5: Strings

### Lab B (w05Blab): Strings
- **Bank Statement Processing**
  - String splitting with `.split()`
  - Type conversions (string to int/float/bool)
  - Transaction list building
  - Formatted output with string formatting
  - Table formatting with alignment and widths

### Lecture B (w05Blec): Strings
- **String Operations**
  - String as a sequence (indexing, slicing, len, in)
  - String addition and multiplication
  - Search methods: `.find()`, `.startswith()`, `.endswith()`
  - Modification: `.replace()`, `.upper()`, `.lower()`
  - Splitting and joining with delimiters

- **String Formatting**
  - f-strings for variable interpolation
  - Format specifications for numbers
  - Table formatting examples
  - Unicode emojis

### Discussion (w05disc): VSCode and Debugging
- **Development Environment**
  - VSCode installation
  - Python environment setup
  - Package installation with pip
  - Virtual environments with venv

- **Debugging**
  - Breakpoints and step-through execution
  - Variable inspection
  - Debug panel usage
  - Common debugging patterns

---

## Week 6: Files and Modules

### Lab A (w06Alab): Files
- **Pathlib Module**
  - Directory creation with `Path.mkdir()`
  - File creation with `Path.touch()`
  - Path existence checking
  - Directory iteration with `.iterdir()`
  - File extension extraction with `.suffix`

- **NumPy File I/O**
  - Loading CSV data with `np.loadtxt`
  - Saving binary files with `.npy` extension
  - Air quality data analysis
  - Correlation coefficient calculation with `np.corrcoef`
  - Linear regression visualization

### Lecture A (w06Alec): Working with Files
- **Pathlib Package**
  - Cross-platform path handling
  - Directory iteration patterns

- **Text File Operations**
  - Writing with `open(..., 'w')`
  - Reading with `open(..., 'r')`
  - Context managers (with statements)

- **Pickle Module**
  - Serializing Python objects
  - Saving complex data structures
  - Loading pickled data

- **NumPy File Operations**
  - Text file I/O: `np.savetxt`, `np.loadtxt`
  - Binary file I/O: `np.save`, `np.load`
  - Multiple variables: `np.savez`, `np.load`

### Lab B (w06Blab): Modules
- **Module Creation**
  - Converting notebook code to `.py` files
  - Function definitions in modules
  - Default parameter values
  - Error handling for invalid operations

- **Module Usage**
  - Importing with `from module import function`
  - Aliasing with `as` keyword
  - Running modules as scripts with `if __name__=="__main__"`
  - Command-line argument access with `sys.argv`

### Lecture B (w06Blec): Modules
- Import patterns
- Function aliasing
- Module organization best practices

### Discussion (w06disc): Using Files and Modules in Simulation
- Integration of file I/O and modules
- Simulation workflow organization
- Data persistence strategies

---

## Week 7: Matplotlib Visualization

### Lab A (w07Alab): Matplotlib
- **Scatter Plots**
  - Loading 2D data from CSV
  - Figure and axes creation with `plt.subplots`
  - Marker customization (color, size, style)
  - Axis limits and tick configuration
  - Grid, labels, and title formatting
  - Spine manipulation

- **Line Plots**
  - Polynomial approximations (linear and cubic)
  - Multiple data series overlay
  - Legend creation
  - Line style and marker customization

- **Histograms**
  - Data loading from `.npy` files
  - Subplot arrangement (multiple rows)
  - Bin count and width configuration
  - Color and transparency settings

### Lecture A (w07Alec): Matplotlib Part 1
- **Figure Creation Methods**
  - `plt.figure()` + `plt.subplot()`: Matlab-style, stateful
  - `plt.subplots()`: Recommended, stateless, supports sharex/sharey
  - `fig.add_subplot()`: Stateless, flexible layouts

- **Basic Plot Types**
  - `plot`: Line plots
  - `scatter`: Scatter plots
  - `bar`: Bar charts
  - `hist`: Histograms

- **Additional Types**
  - `imread`: Image display
  - `stem`: Stem plots
  - `fill_between`: Area fills

### Lab B (w07Blab): 3D Plots and Animations
- **3D Line Plots**
  - Loading trajectory data from `.npy`
  - 3D axes with `projection='3d'`
  - Starting point and highest point marking
  - Legend in 3D space
  - Interactive rotation with `%matplotlib widget`

- **Surface Plots**
  - Meshgrid creation with `np.meshgrid`
  - Function evaluation on 2D grids
  - Surface plotting with `plot_surface`
  - Colormap and transparency settings
  - Regular vs. irregular grids

### Lecture B (w07Blec): Matplotlib Part 2
- **3D Plotting**
  - Adding 3D projection to axes
  - Wireframe and surface plots
  - Irregular grid triangulation with `matplotlib.tri`

- **Animations**
  - `FuncAnimation` for dynamic plots
  - Update function patterns
  - Line, bar, and histogram animation
  - Saving animations as GIF/video

### Discussion (w07disc): Animations in Matplotlib
- **Animation Techniques**
  - Legend addition and spine customization
  - Drone trajectory animation
  - Line object setters: `set_data_3d`, `set_color`, etc.
  - Bar object setters: `set_height`, etc.
  - Scatter object setters: `set_facecolor`, etc.
  - Surface plot animation challenges
  - Animation saving with `.save()`

---

## Week 11: Numerical Differentiation

### Lab A (w11Alab): Numerical Differentiation
- **Ant on a Wire Problem**
  - Loading position vs. time data
  - Plotting measured data
  - Time step calculation from uniform spacing

- **Finite Difference Methods**
  - Forward differencing: f'(t) = (f(t+h)-f(t))/h
  - Backward differencing: f'(t) = (f(t)-f(t-h))/h
  - Central differencing: f'(t) = (f(t+h)-f(t-h))/(2h)
  - Handling boundary conditions with np.nan

- **Speed Analysis**
  - Comparing three differentiation methods
  - Turn-back counting (positive to negative transitions)
  - Velocity profile analysis

---

## Week 12: Numerical Integration and Root Finding

### Lab A (w12Alab): Volume Estimation
- **Spherical Container Volume**
  - Volume formula: V = (πh²/3)(3r-h)
  - Total volume calculation
  - Volume vs. height plotting
  - Root finding for target volume

- **Bisection Method**
  - Step count calculation: ceil(log₂(|P₀-N₀|/ε))
  - Algorithm implementation with interval halving
  - Sequence tracking and convergence
  - Comparison plotting with solution line

- **Newton-Raphson Method**
  - Derivative calculation
  - Iterative formula: x_{k+1} = x_k - f(x_k)/f'(x_k)
  - Convergence criteria (x-tolerance and f-tolerance)
  - NaN handling for early termination
  - Comparison with bisection method

### Lab B (w12Blab): Fixed-Point Iteration
- **Colebrook Equation**
  - Friction factor calculation in fluid mechanics
  - Equation transformation with variable substitution
  - Fixed-point iteration implementation
  - Convergence checking with derivative estimation

- **Multi-variable Systems**
  - System of nonlinear equations
  - Multi-variable fixed-point iteration
  - Variable transformations for improved convergence
  - Different g-function strategies

### Discussion (w12disc): Solving Nonlinear Systems with FPI
- **System Analysis**
  - Grid-based function evaluation
  - Root visualization with contour plots
  - Initial condition grid generation
  - Convergence basin analysis
  - Transformation strategies (ξ → η variables)

---

## Week 13: Linear Algebra and Transformations

### Lab A (w13Alab): Isometric Projection
- **Matrix Multiplication**
  - NumPy `@` operator for matrix multiplication
  - Matrix-vector and vector-matrix products

- **Isometric Projection**
  - 3D point cloud loading and visualization
  - Rotation matrices for 3D transformations
  - 45° rotation about z-axis
  - Rotation about y' by atan(1/√2)
  - Coordinate relabeling for projection
  - Sequential transformation application

### Lecture A (w13Alec): Matrix Multiplication
- NumPy matrix multiplication methods
- Column vector vs. row vector operations
- Shape considerations in multiplication

### Lab B (w13Blab): Temperature Distribution
- **Linear System Setup**
  - Node coordinate to index mapping
  - Measured vs. unmeasured node classification
  - Neighbor identification for averaging
  - Matrix form construction: Ax = b
  - Rank analysis for solution existence

- **Linear Algebra Solution**
  - Matrix rank computation with `np.linalg.matrix_rank`
  - Extended matrix (A|b) rank analysis
  - Solution existence/uniqueness determination
  - Matrix inversion with `np.linalg.inv`
  - Temperature matrix reconstruction
  - 3D surface visualization

### Discussion (w13disc): Solving Forces in a Crane
- Force balance equations
- Linear system formulation
- Solution analysis with linear algebra

---

## Week 14: Differential Equations

### Lab A (w14Alab): Simulating Heating and Cooling
- **Newton's Law of Cooling**
  - ODE: T'(t) = -α(T(t)-T_a)
  - Exact solution: T(t) = T_a + (T₀-T_a)e^(-αt)
  - State equation implementation
  - Time grid generation

- **Euler's Method**
  - First-order numerical integration
  - Generic IVP solver implementation
  - Slope estimator pattern
  - Error analysis vs. time step

- **Higher-Order Methods**
  - Midpoint method implementation
  - Heun's method (improved Euler)
  - Time-varying ambient temperature
  - Method comparison and accuracy

### Lab B (w14Blab): Interconnected Water Tanks
- **Three-Tank System**
  - State vector: y = (h₁, h₂, h₃)
  - Flow equations with proportional differences
  - Matrix form: y' = Ay + w
  - Closed system (no supply/demand)

- **Multi-variable IVP Solver**
  - Vector-valued state equations
  - Euler's method for systems
  - Runge-Kutta 4 (RK4) implementation
  - State trajectory visualization in 3D

- **Open System with Supply/Demand**
  - Time-varying supply and demand profiles
  - Modified state equations with w(t)
  - RK4 adaptation for time-varying inputs
  - Realistic simulation scenarios

### Lecture A (w14Alec): Not present in workspace

### Lecture B (w14Blab): Not present in workspace

### Discussion (w14disc): Randomness in Python with SciPy
- **Random Sampling**
  - Normal distribution: `scipy.stats.norm`
  - Uniform distribution: `scipy.stats.uniform`
  - Discrete distributions: `scipy.stats.rv_discrete`
  - Sampling with `.rvs()` method
  - Histogram visualization

---

## Week 15: Monte Carlo Simulation

### Lab A (w15Alab): Randomness and Monte Carlo
- **Pumpkin Seed Analysis**
  - Loading CSV data for two seed types
  - Sample statistics (mean, standard deviation)
  - Histogram comparison with overlapping distributions
  - Statistical visualization

- **Basketball Free Throw Simulation**
  - Physics model: drag force and gravity
  - State equation: 4-ODE system (position and velocity)
  - SciPy `solve_ivp` for trajectory computation
  - Success criteria: hoop intersection
  - Monte Carlo ensemble with random initial conditions
  - Success rate estimation from ensemble

### Lecture A (w15Alec): Monte Carlo Pendulum
- **Pendulum Dynamics**
  - Equation of motion with damping
  - Energy calculation: E = mgL(1-cos(y)) + ½m(Ly')²
  - Gaussian initial condition distribution
  - Ensemble simulation with solve_ivp
  - Energy distribution analysis

### Lecture B (w15Blec): Lorenz Attractor
- **Lorenz System**
  - Chaotic 3D system: x' = σ(y-x), y' = x(ρ-z)-y, z' = xy-βz
  - Standard parameters: σ=10, ρ=28, β=8/3
  - 3D trajectory visualization
  - Sensitive dependence on initial conditions
  - Monte Carlo ensemble simulation
  - Animation of ensemble evolution

### Lecture B (w15Blec): Multiprocess Simulation
- **Parallel Computing**
  - Serial Monte Carlo baseline
  - Multiprocessing with `multiprocessing.Pool`
  - Function packaging for parallel execution
  - Initial condition ensemble as list
  - Performance comparison: serial vs. parallel
  - Speedup analysis

---

## Key Libraries and Tools

### Core Python
- **Built-in modules**: `random`, `math`, `cmath`, `csv`, `pathlib`, `pickle`
- **Control structures**: if/elif/else, for, while, break, continue
- **Data structures**: lists, tuples, sets, dictionaries, strings
- **Functions**: definition, default parameters, multiple returns, lambda

### Scientific Computing
- **NumPy**: Array operations, broadcasting, linear algebra, file I/O
- **SciPy**: Integration (`solve_ivp`, `cumulative_trapezoid`), statistics, constants
- **Matplotlib**: 2D/3D plotting, animations, customization

### Development Tools
- **Jupyter Notebooks**: Interactive development, visualization
- **VSCode**: Code editing, debugging, Git integration
- **Otter Grader**: Autograding, Gradescope integration
- **Git**: Version control (implied through workspace structure)

---

## Programming Patterns and Best Practices

### Numerical Methods
- **Finite differences**: Forward, backward, central differencing
- **Integration**: Trapezoidal rule, Euler's method, RK4
- **Root finding**: Bisection, Newton-Raphson, fixed-point iteration
- **ODE solving**: State equations, initial value problems, SciPy solvers

### Data Analysis
- **Vectorization**: NumPy array operations instead of loops
- **Boolean masking**: Efficient filtering and selection
- **Aggregation**: Mean, std, sum, min, max along axes
- **Visualization**: Appropriate plot types for data exploration

### Code Organization
- **Modules**: Reusable code in .py files
- **Functions**: Single responsibility, clear inputs/outputs
- **Documentation**: Comments, docstrings, variable naming
- **Testing**: Autograder compatibility, edge case handling

### Performance Considerations
- **Pre-allocation**: NumPy arrays with known size
- **Broadcasting**: Avoid explicit loops for array operations
- **Parallel computing**: Multiprocessing for Monte Carlo ensembles
- **Memory management**: Efficient data structures for large simulations

---

## Applications and Case Studies

### Physics Applications
- Projectile motion (phone falling, bouncing ball)
- Vibrating systems (rod vibration, pendulum)
- Thermodynamics (cooling law, heat conduction)
- Fluid dynamics (water tanks, drag force)
- Electromagnetics (Colebrook equation)

### Engineering Applications
- Structural analysis (crane forces)
- Measurement systems (temperature sensors)
- Control systems ( interconnected tanks)
- Computer graphics (isometric projection)
- Signal processing (ant trajectory)

### Data Science Applications
- Statistical analysis (pumpkin seeds)
- Pattern recognition (voting analysis)
- Monte Carlo methods (free throws, Lorenz system)
- Optimization (volume estimation, root finding)
- Machine learning preparation (data preprocessing)

---

## Assessment and Submission

### Grading Structure
- **Lab sessions**: Hands-on coding exercises with autograder
- **Discussion sessions**: Practice problems and debugging
- **Lecture sessions**: Concept introduction and examples
- **Autograder**: Otter grader with immediate feedback
- **Gradescope**: Submission platform with zip file export

### Submission Process
1. Complete all cells in notebook
2. Run all cells to ensure outputs are generated
3. Save notebook
4. Run `grader.export(pdf=False)` to create zip file
5. Submit zip file to Gradescope

### Common Pitfalls
- Non-sequential cell execution
- Hard-coded values instead of variables
- Incorrect data types (int vs. float)
- Off-by-one errors in indexing
- Forgotten imports
- Inconsistent random seed usage in Monte Carlo

---

### Documentation
- Python documentation: docs.python.org
- NumPy documentation: numpy.org/doc
- SciPy documentation: docs.scipy.org
- Matplotlib documentation: matplotlib.org/stable

### Textbooks and References
- Course-specific notebooks and templates
- Online documentation for all libraries
- Scientific computing references
- Engineering mathematics handbooks

---

*This summary covers all 15 weeks of the E7 course, from basic Python fundamentals to advanced numerical methods and Monte Carlo simulation techniques.*
