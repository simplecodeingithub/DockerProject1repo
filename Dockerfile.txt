# Use an official Redis image as the base
FROM redis:latest

# Update system packages and
RUN apt-get update

# Create a text file
RUN echo "This is a sample text file created during Docker image build." > /sample.txt

