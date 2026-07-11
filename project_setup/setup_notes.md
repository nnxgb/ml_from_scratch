
## Step 1
``` bash
uv init
uv add pandas plotly quarto-cli
source .venv/bin/activate

quarto create-project . --type website
ml_scratch % mkdir src && cd src
```

# Step 2:
Get styles.css from claude code and paste it at project root.
Use theme guide for development

# Step 3: 
`quarto preview` for live development
`quarto render` for site creation

Create a github public repo and push the code.
