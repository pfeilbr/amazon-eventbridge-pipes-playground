# amazon-eventbridge-pipes-playground

learn [Amazon EventBridge Pipes](https://docs.aws.amazon.com/eventbridge/latest/userguide/eb-pipes.html)

## concepts

- create **point-to-point integrations** between event producers and consumers with optional transform, filter and enrich steps
- removes the need for "glue" lambdas
- high-level concepts:
  - [sources](https://docs.aws.amazon.com/eventbridge/latest/userguide/eb-pipes-event-source.html)
  - [source event filter](https://docs.aws.amazon.com/eventbridge/latest/userguide/eb-pipes-event-filtering.html)
  - [transform and enrich](https://docs.aws.amazon.com/eventbridge/latest/userguide/eb-pipes-input-transformation.html)
  - [targets](https://docs.aws.amazon.com/eventbridge/latest/userguide/eb-pipes-event-target.html)

![Amazon EventBridge Pipes Process](https://docs.aws.amazon.com/images/eventbridge/latest/userguide/images/pipes_overview.png)

## resources

- [New — Create Point-to-Point Integrations Between Event Producers and Consumers with Amazon EventBridge Pipes](https://aws.amazon.com/blogs/aws/new-create-point-to-point-integrations-between-event-producers-and-consumers-with-amazon-eventbridge-pipes/)
- [Amazon EventBridge Pipes](https://docs.aws.amazon.com/eventbridge/latest/userguide/eb-pipes.html)
- [AWS::Pipes::Pipe](https://docs.aws.amazon.com/AWSCloudFormation/latest/UserGuide/aws-resource-pipes-pipe.html)
  - CloudFormation examples  [sourcegraph: lang:yaml 'AWS::Pipes::Pipe'](https://sourcegraph.com/search?q=context:global+lang:yaml+%27AWS::Pipes::Pipe%27&patternType=standard&sm=1&groupBy=repo)