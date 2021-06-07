{% assign employer1 = "New Jersey Institute of Technology, Newark, NJ" %}
{% assign employer2 = "Burlington Coat Factory, Burlington, NJ" %}
{% assign BSdegree = "B.S in Information Technology"%}
{% assign MSdegree = "M.S in Computer Science"%}

{% assign jobDescNJIT = 
        
       "Responsible for maintaining the day to day responsibilities of the Application Information Systems department.    
        Supported and revised critical Groovy and PHP applications such as Admission Fall 2019, Full Time Certification, Schedule Builder, and more.     
        Helped implement third party solutions by Ellucian as old applications retired and continued support.
        Installed and administered development environments for all the in-house NJIT application.
        Generated daily reports using IBM Cognos reporting tool"
%}

{% assign jobDescBurl = 
    
        "Refined the communication layer for an API client library using Java's HttpUrlConnection and cURL. Parsed returned JSON data to Java POJOs using Jersey for the API client library.
    
        Responsible for designing and implementing the underlying hierarchical data structure for the in-house application.. 
    
        Refined and remodeled the application framework to overcome Java 1.7's lack of default interface behavior
    
        Developed responsive GUI components adhering to business requirements with Java Swing and JDBC using the MVC pattern.
    
        Raised and resolved defects for Allocation Management System the internal application on a day to day basis."
%}        
        
        



{% capture jobDesc %} 
    
    ### {{employer1 | upcase}}
    
    {% capture newLine %}
    {% endcapture %}

    {{jobDescNJIT }}
    
{%endcapture%}
