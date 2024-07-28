# Resiliency Patterns in Microservices

## Circuit Breaker Pattern

Fail fast in case of errors and enables you to perform the default or fallback operations

## Retry Pattern

Making several attempts to execute a failed remote operation before giving up and reporting it as an issue.

## Timeouts

Set a time limit for a remote operation instead of indefinitely waiting for response.

## Health Checks

Monitor the remote services and remove from the load balancer automatically or stop routing requests when it is 
unhealthy

## Fail-over and Redundancy

Redundancy and failover capabilities ensures that if one instance or component fails, another can take over.

## Fallback Mechanism

Fallback mechanisms provide an alternative response or behaviour when a remote operation is failing. 
