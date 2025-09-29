# ✍️ Ray Tracing in One Weekend

## 🚀 Project Overview

This is an implementation of **Ray Tracing in One Weekend** book.


![A simple scene rendered with the Ray Tracer, showing spheres with metal, dielectric, and diffuse materials.](images/render_output.png)

The current output of the ray tracer is a static image file (PPM format)

---

## 📦 Getting Started

### Prerequisites

You will need a C++ compiler installed on your system.

### Building the Project

Follow these steps to clone and build the project on your machine.

**1. Clone the repository:**

```bash
git clone [https://github.com/](https://github.com/)[Your-Username]/graphics.git
cd graphics


# Compile the main.cc file
g++ main.cc -o raytracer

# Optional: Add compiler optimizations and warnings for better performance/safety
# g++ -Wall -O3 main.cc -o raytracer

# Run the executable and save the output to an image file
./raytracer > image.ppm
```
