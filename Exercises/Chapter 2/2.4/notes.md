## Partial Derivatives and Gradients

Given $f: \mathbb{R}^n \to \mathbb{R}$ and vector $\mathbf{x} = [x_1, x_2, \dots, x_n]$.

We have: 

- For all $\mathbf{A} \in \mathbb{R}^{m \times n}$, then $\nabla_{\mathbf{x}} \mathbf{A} \mathbf{x} = \mathbf{A}^\top$ and $\nabla_{\mathbf{x}} \mathbf{x}^\top \mathbf{A} = \mathbf{A}$. (Because we define that $dy = (\nabla_x y)\top dx$, so $\nabla_x y = J^T$ and $J$ is the Jacobian matrix)

- And for square matrix $\mathbf{A} \in \mathbb{R}^{n \times n}$, $\nabla_{\mathbf{x}} \mathbf{x}^\top \mathbf{A} \mathbf{x} = (\mathbf{A} + \mathbf{A}^\top)\mathbf{x}$.