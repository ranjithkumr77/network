# #!/bin/bash

# Script to check age ranges

echo "Enter your age:"
read age

if [ "$age" -lt 0 ]; then
  echo "Invalid age. Please enter a valid age."
elif [ "$age" -ge 0 ] && [ "$age" -lt 13 ]; then
  echo "You are a child."
elif [ "$age" -ge 13 ] && [ "$age" -lt 18 ]; then
  echo "You are a teenager."
elif [ "$age" -ge 18 ] && [ "$age" -lt 65 ]; then
  echo "You are an adult."
else
  echo "You are a senior citizen."
fi
#!/bin/bash
./agecheck.sh
