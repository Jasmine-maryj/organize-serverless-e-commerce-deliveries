# organize-serverless-e-commerce-deliveries

Step Functions is a serverless orchestration service that lets you easily coordinate multiple Lambda functions into flexible workflows that are easy to debug and change. Step Functions will keep your Lambda functions free of additional logic by triggering and tracking each step of your application for you.
There is the possibility of a race condition if both delivery workers respond at the same time. Step functions handles race conditions and ensures that only one response is accepted and all others are rejected.

<p>
  <img src="https://github.com/Jasmine-maryj/organize-serverless-e-commerce-deliveries/blob/main/output/state-machine.jpg" align="left" width="490" alt="state-machine">
  <img src="https://github.com/Jasmine-maryj/organize-serverless-e-commerce-deliveries/blob/main/output/cloudwatchlogs.jpg" align="right" width="420" alt="state-machine">
</p>


