# Summary
An api to get all departments and related course

## Use Cases
When developer create a search function, search by department is needed. It is required to have an api list all departments

## Risks
It is likely some write "departments & course" as hard code. Hence ,this api is useless, but it is a bad practice.

## Implementation details
It is a basic api.
Get data from scrap website. It is relative solid. So it won't change frequntly.
example response:
{
    "department":"HEALTH SCIENCES",
    "programs":"Nursing",
    "course": [
        {"course_name":"Academic Foundations for Potential Nursing Applicants"},
        {"course_name":"Nursing(Bachelor of Science)"}
    ]
}