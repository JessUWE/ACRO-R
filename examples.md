# Examples

## Interactive Notebook

For comprehensive examples and tutorials, see our interactive R notebook:

[Example Notebook](articles/example-notebook.html)

## Quick Start Examples

### Basic Usage

```r
library("acro")

# Initialize ACRO
acro_init(suppress = TRUE)

# Your analysis code here
# ACRO will automatically check outputs for disclosure risks
```

### Creating Safe Tables

```r
# Example of creating a cross-tabulation with ACRO
result <- acro_crosstab(data$variable1, data$variable2)

# ACRO automatically applies disclosure control
print(result)
```

### Finalizing Your Session

```r
# When you're done with your analysis
acro_finalise()
```

For more detailed examples and use cases, please refer to the [Example Notebook](articles/example-notebook.html).
