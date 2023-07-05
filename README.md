
# DBMS

## Data models:-
Data Model is the modeling of the data description, data semantics, and consistency constraints of the data. It provides the conceptual tools for describing the design of a database at each level of data abstraction.

### Types of Data Models
#### i) ER Model :->
    * It is a high level data model based on a perception of a real world that consists of a collection of
      entities and of relationships among these objects.
    * Graphical representation of ER Model is ER diagram, which acts as a blueprint of DB.

* Entity: An Entity is a “thing” or “object” in the real world that is distinguishable from all other objects.
    *  It has physical existence.
    *  Each student in a college is an entity.
    *  Entity can be uniquely identified. (By a primary attribute, aka Primary Key)


    1.   Strong Entity: Can be uniquely identified.
    2.   Weak Entity: An entity that depends on another entity called a weak entity. The weak entity doesn't contain any key attribute of its own. The weak entity                        is represented by a double rectangle.
    3.   Weak entity depends on strong entity for existence.
     
    * Entity set
  
      1. It is a set of entities of the same type that share the same properties, or attributes.
      2. E.g., Student is an entity set.
      3. E.g., Customer of a bank
     
    * Attributes
  
      1. An entity is represented by a set of attributes.
      2. The attribute is used to describe the property of an entity. Eclipse is used to represent an attribute..
      3. For each attribute, there is a set of permitted values, called the domain, or value set, of that attribute.
      4. E.g., Student Entity has following attributes
      
      A. Student_ID
      B. Name
      C. Standard
      D. Course
      E. Batch
      F. Contact number
      G. Address
      
* Types of Attributes
  
    * Simple
      
        1. Attributes which can’t be divided further.
        2. E.g., Customer’s account number in a bank, Student’s Roll number etc.
        
    * Composite
      
        1. Can be divided into subparts (that is, other attributes).
        2. E.g., Name of a person, can be divided into first-name, middle-name, last-name.
        3. Address can also be divided, street, city, state, PIN code.

    * Single-valued
       
        1. Only one value attribute.
        2. e.g., Student ID, loan-number for a loan.
        
    * Multi-valued
      
        1. Attribute having more than one value.
        2. e.g., phone-number, nominee-name on some insurance, dependent-name etc.
        3. Limit constraint may be applied, upper or lower limits.
        
    * Derived
      
        1. Value of this type of attribute can be derived from the value of other related attributes.
        2. e.g., Age, loan-age, membership-period etc.
        
    * NULL Value
      
        1. An attribute takes a null value when an entity does not have a value for it.
        2. It may indicate “not applicable”, value doesn’t exist. e.g., person having no middle-name
        3. It may indicate “unknown”.
           
        1. Unknown can indicate missing entry, e.g., name value of a customer is NULL, means it is missing as name
        must have some value.
        2. Not known, salary attribute value of an employee is null, means it is not known yet.
           
#### ii) 
