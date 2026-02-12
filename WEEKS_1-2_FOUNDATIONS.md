# Week 1-2: Foundations of SAP S/4HANA CDS Views

## Theory
SAP Core Data Services (CDS) are a set of database table definitions used in SAP S/4HANA that define specific business entities and relationships. CDS provides a way to define semantically-rich data models which can be consumed by various UI technologies like Fiori and SAP Analytics Cloud.

### Key Concepts:  
- **Definition:** CDS views are SQL-based views that may include complex business logic, associations, and annotations.  
- **Annotations:** Metadata that provides additional information like semantics to the CDS view's fields.  
- **Associations:** Define relationships between different CDS views that allow joining data in a more meaningful way compared to traditional SQL joins.

### Advantages:  
- Improved data modeling.  
- Performance optimization using native SQL functions.  
- Enhanced usability for frontend applications.

## Hands-on Exercises
1. **Creating a Basic CDS View**:  
   - Open ABAP Development Tools in Eclipse.  
   - Select the package to create the CDS view.  
   - Right-click > New > Other > Core Data Services > Data Definition.
   - Define your CDS view using SQL SELECT statement.

2. **Adding Annotations:**  
   - Use the `@Annotation` syntax to add descriptions, labels, and other semantic information to your CDS fields.  

3. **Defining Associations:**  
   - Demonstrate adding associations between multiple CDS views to create a singular representation of multiple entities.

## Common Mistakes
- Forgetting to activate the CDS view after creation.  
- Overusing annotations which may lead to complexity.  
- Failing to handle null values properly, leading to unwanted results in UI applications.  

## Debugging Tips
- Use the SQL Console within Eclipse to test your CDS queries.  
- Check the activation of your CDS view regularly to catch errors early.  
- Utilize transaction code SE11 to inspect data structures and view definitions if you encounter issues.

## Checkpoint Quizzes
1. **Quiz Questions:** 
   - What is the purpose of annotations in CDS views?  
   - Explain the difference between joins and associations in CDS views.  
   - Identify potential pitfalls while creating CDS views.

2. **Answers:**  
   - Annotations provide metadata about the view.  
   - Joins are SQL-based, while associations enhance CDS views.
   - Common pitfalls include forgetting to activate and mismanaging null values.

## Summary
In Weeks 1-2, we covered foundational concepts of SAP S/4HANA CDS Views, their uses, alongside practical exercises designed to reinforce learning and understanding. Through this content, learners should feel more competent in developing CDS views and troubleshooting common issues they may encounter.