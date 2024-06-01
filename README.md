# project-1
Customer Advisory
Overview
The following diagram is a simplified On-Prem e-commerce architecture of a startup. It involves
various components such as servers, databases, payment gateways, inventory management
systems, and website interfaces.
Flow
1. The initial request originates from the user, which can be a browser or hand-held device.
2. The user is presented with a standard home page with an option of login (or sign up)
3. Once the authentication is complete, the user is presented with a more detailed page of
various products.
4. The user now shops and fills the cart and checks out.
5. The backend server processes the request.
6. The warehouse looks up the order and prepares for dispatch.
7. A notification is sent to the customer with various updates.
8. The shipment is dispatched and reaches the customer.
Bill of materials
1. The file storage is 5TB in size.
2. The database is open-source MySQL version 8 running on a server with 16 CPUs, 64GB
RAM, and 2TB SSD. A backup server with the exact specifications runs the secondary
database.
3. The user authentication layer and API Gateway are implemented together and run on 3
instances, each with 4CPU, 8GB RAM, and 512GB HDD.
4. The server tier has 10 servers, each with 8CPU, 32GB RAM, and 512GB SSD.
5. The warehouse systems are all hand-held devices. An estimated 50 such devices
access the warehouse application hosted in the server tier.
6. The technical IT staff comprises of 1 architect, 1 technical lead, 5 DevOps engineers, 1
networking engineer, 1 DBA.

 Questions
1. Calculate the overall on-prem cost for the e-commerce architecture. State all the
assumptions. You can omit the costs related to the IT staff. – 20 points
2. The organization wants to migrate the application to the cloud (Lift and Shift). What risks
do you anticipate? – 5 points
3. Calculate the projected cost of the architecture on the cloud. – 15 points
4. Advanced (Optional)
a. Replace the migrated lift-and-shift application with cloud-native services. State all
assumptions.
b. Calculate the cost of the resulting final cloud-native architecture.
