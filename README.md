# Achilleiou.github.io
# Check out solution URL
$ cat solution.txt
Achilleiou.github.io
# Ensure the URL exists
$ curl --output /dev/null --silent --head --fail Achilleiou.github.io && \
echo "URL exists" || echo "URL does not exist"
URL exists
