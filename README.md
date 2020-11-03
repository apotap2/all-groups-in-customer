# AdminSDK, List All Groups In Customer

This script uses the AdminSDK to list all groups in your customer.

## Prerequisites

Clone this repository.

```
mkdir all-groups-in-customer
cd all-groups-in-customer
git clone https://github.com/jmathai-google/all-groups-in-customer.git ./
```

You'll need python 2.7 installed to run this script. It's recommended that you run this command inside of a `virtualenv`.

```
pip install -r requirements.txt
```

## Set up authentication and authorization

Follow [these steps](https://developers.google.com/admin-sdk/directory/v1/quickstart/python) to set up authentication and authorization. This script will require you to log in with a user who has the admin role to read all groups in your customer.

## Run the script

```
python run.py
```
