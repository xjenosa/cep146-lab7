# Create a new repository
mkdir my-portfolio
cd my-portfolio
git init

# Create initial portfolio file
cat > portfolio.md << 'EOF'
# My Portfolio

## About Me
Name: [Your Name]
Major: Computer Science

## Skills
- Programming: Basic
- Git: Learning

## Projects
- Project 1: TBD
- Project 2: TBD

## Contact
Email: student@university.edu
EOF

git add portfolio.md
git commit -m "Initial portfolio"
