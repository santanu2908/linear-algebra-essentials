# Linear Algebra Essentials

A beginner-friendly collection of Jupyter notebooks covering the essentials of linear algebra with clear NumPy code and visualizations. Ideal for students and self-learners.

## Contents

- **Vectors**: Addition, scalar multiplication, magnitude
- **Basis Vectors**: i-hat, j-hat, linear combinations
- **Linear Transformations**: Rotation, shear, and their effects
- **Matrix Multiplication**: Composition of transformations
- **Dot Product**: Projection, alignment, angle between vectors
- **Determinant**: Area scaling, singularity, flipping
- **Eigenvalues & Eigenvectors**: Invariant directions and scaling
- **Matrix Inverse**: How to compute and visualize the inverse
- **Rank of a Matrix**: Linear independence and dimension
- **Cross Product (3D)**: Perpendicular vector in 3D space

## Where This Lives in AI

Everything you've learned maps directly to the systems you're building. Here's the full picture.

| 3B1B Concept | NumPy Tool | Where in AI |
|---|---|---|
| Vectors | `np.array([...])` | Word embeddings, query vectors, document chunks in RAG |
| Magnitude | `np.linalg.norm()` | Normalizing embeddings before cosine similarity |
| Linear Transformation | `matrix @ vector` | Every neural network layer: `output = W @ input + b` |
| Dot Product | `np.dot()` / `@` | Attention scores in transformers, cosine similarity in RAG retrieval |
| Matrix Multiplication | `A @ B` | Batched forward passes, QKV projections in attention |
| Determinant | `np.linalg.det()` | Checking if weight matrices are well-conditioned |
| Eigenvectors | `np.linalg.eig()` | PCA for visualizing embedding spaces, SVD in recommendation systems |

## Files

- `linalg_notebook_simple.ipynb`: Step-by-step notebook with explanations and plots
- `requirements.txt`: List of required Python packages

## Getting Started

1. **Clone the repository**
   ```bash
   git clone https://github.com/your-username/linear-algebra-essentials.git
   cd linear-algebra-essentials
   ```
2. **Set up your environment**
   - (Recommended) Create a virtual environment:
     ```bash
     python3 -m venv venv
     source venv/bin/activate
     ```
   - Install dependencies:
     ```bash
     pip install -r requirements.txt
     ```
3. **Launch Jupyter Notebook**
   ```bash
   jupyter notebook
   ```
4. **Open `linalg_notebook_simple.ipynb` and run the cells**

## Usage
- Each section introduces a new concept with code and a plot.
- Run cells in order for best results.
- Experiment by changing values and re-running cells to deepen your understanding.

## License
MIT License

---

Feel free to contribute or suggest improvements!
