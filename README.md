## Setup
```bash
git clone git@github.com:nogaki/mysqd_example.git
cd mysqd_example
python -m venv venv 
source venv/bin/activate 
pip install --upgrade pip 
pip install numpy scipy h5py ipykernel qiskit matplotlib
ipython kernel install --user --name=venv
git clone git@github.com:nogaki/pyscf.git
cd pyscf/pyscf/lib/
mkdir build
cd build/
cmake ..
make
cd ../../..
pip install -e .
pip install qiskit qiskit_addon_sqd
```
