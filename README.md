# Genetic Algorithm Image Generation

This project demonstrates the use of a genetic algorithm to generate an image using squares. The algorithm evolves a population of square configurations to approximate a given target image.

## Getting Started

These instructions will help you set up and run the genetic algorithm to generate images using squares. You can run this project in a Jupyter notebook, Google Colab, or your local Python environment.

### Prerequisites

Before you begin, make sure you have the following dependencies installed:

- OpenCV (for image processing)
- DEAP (Distributed Evolutionary Algorithms in Python)
- NumPy (for numerical operations)

You can install these dependencies using pip:

```
pip install opencv-python-headless
pip install deap
pip install numpy
```

### Running the Genetic Algorithm

Follow these steps to run the genetic algorithm:

1. Clone the repository to your local machine:

   ```
   git clone https://github.com/yourusername/genetic-algorithm-image-generation.git
   ```

2. Navigate to the project directory:

   ```
   cd genetic-algorithm-image-generation
   ```

3. Replace the `target_image` variable with the image you want to approximate. You can specify the target image's dimensions in the `width` and `height` variables.

4. Customize the `generate_individual`, `custom_crossover`, and `custom_mutation` functions to define how squares are generated, combined, and mutated. The provided code includes placeholders.

5. Execute the main script:

   ```
   python genetic_algorithm.py
   ```

6. The genetic algorithm will run for a specified number of generations, and the best image approximation will be displayed at each generation.

## Customization

You can customize the genetic algorithm and the image generation process by modifying the provided functions and parameters. Experiment with different settings to achieve the desired results.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments

- [DEAP Documentation](https://deap.readthedocs.io)
- [OpenCV Documentation](https://docs.opencv.org/)

## Author

- Your Name
- GitHub: [yourusername](https://github.com/Subhamm18)
