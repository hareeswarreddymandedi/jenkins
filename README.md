# Jenkins Pipeline Fundamentals

Declarative Pipeline examples for learning stages, agents, parameters, environment variables, execution options, and post-build conditions.

## Examples

| File | Focus |
|---|---|
| [Jenkinsfile](Jenkinsfile) | ROBOSHOP agent, parameters, timeout, concurrency control, and post actions |
| [Jenkinsfile.dcl](Jenkinsfile.dcl) | Minimal Build, Test, and Deploy stage structure |

## Run in a Jenkins lab

1. Configure a Jenkins Pipeline job using this repository as its SCM source.
2. Choose `Jenkinsfile` or `Jenkinsfile.dcl` as the script path.
3. For the main example, provide an online Linux agent labeled `ROBOSHOP` with a shell available.
4. Review the parameters, run the job, and inspect its stage output.

## Scope

The stages demonstrate pipeline structure using printed messages. They do not compile, test, or deploy an application. Use Jenkins credentials binding for actual secrets; do not log password values or interpolate untrusted parameters into shell code.

For an application-oriented example, see [catalogue](https://github.com/hareeswarreddymandedi/catalogue).
