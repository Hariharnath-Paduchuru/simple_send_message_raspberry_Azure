# Send a Simple Message from the Raspberry Pi to Azure IoT Hub
This Sample code is used to send a simple message to Azure IoT Hub from Raspberry Pi.

## Running the Python Code on Raspberry Pi

### Prerequisites

- Python 3: Raspberry Pi typically comes with Python pre-installed, but you can ensure you have Python 3 installed by running the following command in the terminal:

    ```
    python3 --version
    ```

    If it's not installed, you can install it by running:

    ```
    sudo apt update
    sudo apt install python3
    ```

### Step 1: Install the Required Packages

- Open a terminal on your Raspberry Pi.

- Run the following command to install the necessary packages:

    ```
    pip3 install azure-iot-device
    ```

### Step 2: Save the Code

- Create a new file on your Raspberry Pi and save the provided Python code into that file, for example, `simple_send_message.py`.

### Step 3: Obtain the Device Connection String

- Replace `<your_device_connection_string>` in the code with the actual connection string for your Azure IoT Hub device. You can find the connection string in the Azure portal under your IoT Hub's "Shared access policies" section.

### Step 4: Run the Code

- Open a terminal on your Raspberry Pi.

- Navigate to the directory where you saved the Python file.

- Run the following command to start running the Python code:

    ```
    python3 simple_send_message.py
    ```

- The code will now start sending a simple message to your Azure IoT Hub device. You should see the message being printed on the console.
- You should use the Azure IoT Explorer to monitor the data received at the IoT Hub.
- To configure the Azure IoT Explorer, look into the steps mentioned [here](https://github.com/Azure/azure-iot-explorer)


That's it! You have successfully run the Python code on your Raspberry Pi to send simple message to your Azure IoT Hub device.
