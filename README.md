Run on TensorFlow 1.1.0, Python 3.5+ 

Tensorflow supports both Python 2.7 and Python 3.3+. **Note that for Windows, TensorFlow supports only 64-bit Python 3.5.** 

Google has a pretty detailed instruction on how to download and setup Tensorflow. You can follow it here: <https://www.tensorflow.org/get_started/os_setup>

## Install TensorFlow

#### With Docker Compose

1. Install [Docker for Windows](https://docs.docker.com/docker-for-windows/)

2. Clone [Github](https://git-scm.com/download/win):

   ```
   $ git clone git@github.com:doquangthanh/docker-python-machine-learning.git
   $ cd docker-python-machine-learning/
   ```

3. Run containers:

   ```
   $ docker-compose up
   tensorflow     |     Copy/paste this URL into your browser when...
   tensorflow     |     to login with a token:
   tensorflow     |         http://localhost:8888/?token=TOKEN
   tensorboard    | Starting TensorBoard b'47' at http://0.0.0.0:6006
   tensorboard    | (Press CTRL+C to quit)
   ```

4. Open iPython Notebook using the URL with the token: <http://localhost:8888/?token=TOKEN>

5. Open TensorBoard at: [http://localhost:6006](http://localhost:6006/)