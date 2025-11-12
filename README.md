# Cloud-Native Web Voting Application with Kubernetes

This cloud-native web application is built using a mix of technologies. It's designed to be accessible to users via the internet, allowing them to vote for their preferred programming language out of six choices: **C#, Python, JavaScript, Go, Java, and NodeJS.**

![Voting App](./Voting-App.png)

## Technical Stack

- **Frontend**: The frontend of this application is built using React and JavaScript. It provides a responsive and user-friendly interface for casting votes.
- **Backend and API**: The backend of this application is powered by Go (Golang). It serves as the API handling user voting requests. MongoDB is used as the database backend, configured with a replica set for data redundancy and high availability.

## Kubernetes Resources

To deploy and manage this application effectively, we leverage Kubernetes and a variety of its resources:

- **Namespace**: Kubernetes namespaces are utilized to create isolated environments for different components of the application, ensuring separation and organization.
- **Secret**: Kubernetes secrets store sensitive information, such as API keys or credentials, required by the application securely.
- **Deployment**: Kubernetes deployments define how many instances of the application should run and provide instructions for updates and scaling.
- **Service**: Kubernetes services ensure that users can access the application by directing incoming traffic to the appropriate instances.
- **StatefulSet**: For components requiring statefulness, such as the MongoDB replica set, Kubernetes StatefulSets are employed to maintain order and unique identities.
- **PersistentVolume and PersistentVolumeClaim**: These Kubernetes resources manage the storage required for the application, ensuring data persistence and scalability.

## Learning Opportunities

Creating and deploying this cloud-native web voting application with Kubernetes offers a valuable learning experience. Here are some key takeaways:

1. **Containerization**: Gain hands-on experience with containerization technologies like Docker for packaging applications and their dependencies.
2. **Kubernetes Orchestration**: Learn how to leverage Kubernetes to efficiently manage, deploy, and scale containerized applications in a production environment.
3. **Microservices Architecture**: Explore the benefits and challenges of a microservices architecture, where the frontend and backend are decoupled and independently scalable.
4. **Database Replication**: Understand how to set up and manage a MongoDB replica set for data redundancy and high availability.
5. **Security and Secrets Management**: Learn best practices for securing sensitive information using Kubernetes secrets.
6. **Stateful Applications**: Gain insights into the nuances of deploying stateful applications within a container orchestration environment.
7. **Persistent Storage**: Understand how Kubernetes manages and provisions persistent storage for applications with state.

By working through this project, you'll develop a deeper understanding of cloud-native application development, containerization, Kubernetes, and the various technologies involved in building and deploying modern web applications.

---

### 🧭 Steps to Deploy

Follow this blog for step-by-step implementation and detailed deployment guidance:  
👉 [Cloud-Native Web Voting Application with Kubernetes](https://medium.com/@siddadeepika/cloud-native-web-voting-application-with-kubernetes-0a70c4f62807)
