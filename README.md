# Enterprise-Network-Design-Security-Project
 
## Objective
 
Congratulations! You and your team have been asked by the IT Manager for Universal Remedies, a Pharmaceutical Company, to design the network and office infrastructure for a new campus.
 
## Scenario
 
Universal Remedies is expanding their operations and have built a new campus in Salt Lake City, UT.
 
- They have regional offices in San Antonio, TX and Vancouver, BC, Canada, but the headquarters are in Chicago, IL.
- The new campus consists of an 8,000 sq. ft. office building and a 6,000 sq. ft. laboratory building (both are single story), about a quarter mile apart (there is general landscaping, sidewalks, and a parking lot separating the two buildings).
### Office Building 
 
- The Regional Manager has an Administrative Assistant and 3 Secretaries.
- The 2 IT staff share an office.
- There are 7 people on the Marketing and Sales staff, split between 3 offices. The VP of Marketing gets their own office.
- The Accountant and the HR rep share an office.
- There are 4 people on the Training staff, split between 2 offices.
- There is a Doctor on staff who has her own office.
- Every office must have at least 6 network drops.
- There is a small conference room which has a large screen for presentations and a conference phone.
- There is a training classroom that should accommodate up to 30 students at a time.
- Everyone needs Internet access and access to internal resources hosted at the headquarters.
### Laboratory 
 
- The Director of Operations has a Pharmacist and a Technician on staff, and they share the Administration space.
  - This space should be connected to the network in the other building and to the Internet.
- The large Conference Room/Classroom can host up to 60 people at a time for various trainings or meetings.
  - This space needs Internet connectivity for guests but needs to be shielded from the rest of the internal network.
  - There should be 4 network drops that are connected to the internal network.
- The Operations Lab consists mostly of test equipment, manufacturing equipment, and specialized medical equipment.
  - This space needs to have its own network that is isolated from all other networks and that is not connected to the Internet.
  - There should be at least 30 network drops in this space.
- The Control Room needs two network drops that are connected to the Operations Lab network and two drops that are connected to the internal network (and Internet).
- The Analytical Lab needs 4 network drops to the Operations Lab network and 4 connected to the internal network (and Internet).
- There needs to be a guest network to provide access to visitors using the classroom spaces (there is a classroom space in both buildings).
- There are services hosted in the cloud or at the Headquarters facility which internal users need access to.
**Drop summary:** 4 network drops for a guest network (classroom), 30 network drops for the operations labs, 4 drops for the control room, and 4 drops for the analytical lab = 46 network drops.
 
## Assignment
 
You are to provide a viable solution for:
 
- Infrastructure of the new campus (including how to connect the two buildings)
- Connectivity back to HQ and to the Internet
- Security
- Backup of data
## Deliverables
 
### Addressing plan
 
- Allow for at least a 50% growth in all areas except for point-to-point links.
- Use private IP addresses where appropriate.
### Topology diagram
 
- Identify hosts and IP addresses.
- Identify VLAN separations.
- Plan for redundancy to provide high availability.
### Bill of Materials of all components
 
- List the part numbers, description, and quantity.
- Include both capital (one-time) and operating (ongoing) expenses.
- Be sure to account for both material and labor costs.
### Security document
 
This is a high-level document that discusses what is allowed and not allowed within your design from a security standpoint (diagrams and tables are recommended).
 
- Consider what ports and protocols will be working in your network.
- Consider what is allowed to connect to which devices (including internal resources, resources that may be at HQ, resources that may be in the Cloud, and the Internet).
- Explain any additional security considerations (both logical and physical).
### Presentation
 
- A slide deck about your design.
- A recording of your presentation:
  - 12-15 minutes long
  - Present as if you are selling your design to a small business for them to adopt it
  - The audience is your fellow classmates
  - Highlight the cool features of your design
