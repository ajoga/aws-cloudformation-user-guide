# AWS Elastic Beanstalk ConfigurationTemplate SourceConfiguration<a name="aws-properties-beanstalk-configurationtemplate-sourceconfiguration"></a>

Use settings from another Elastic Beanstalk configuration template for the [AWS::ElasticBeanstalk::ConfigurationTemplate](aws-resource-beanstalk-configurationtemplate.md) resource type\.

## Syntax<a name="w13ab1c21c10d132c22c23b5"></a>

### JSON<a name="aws-properties-beanstalk-configurationtemplate-sourceconfiguration-syntax.json"></a>

```
{
   "[ApplicationName](#cfn-beanstalk-configurationtemplate-sourceconfiguration-applicationname)" : String,
   "[TemplateName](#cfn-beanstalk-configurationtemplate-sourceconfiguration-templatename)" : String
}
```

### YAML<a name="aws-properties-beanstalk-configurationtemplate-sourceconfiguration-syntax.yaml"></a>

```
[ApplicationName](#cfn-beanstalk-configurationtemplate-sourceconfiguration-applicationname): String
[TemplateName](#cfn-beanstalk-configurationtemplate-sourceconfiguration-templatename): String
```

## Properties<a name="w13ab1c21c10d132c22c23b7"></a>

`ApplicationName`  <a name="cfn-beanstalk-configurationtemplate-sourceconfiguration-applicationname"></a>
The name of the Elastic Beanstalk application that contains the configuration template that you want to use\.  
*Required*: Yes  
*Type*: String

`TemplateName`  <a name="cfn-beanstalk-configurationtemplate-sourceconfiguration-templatename"></a>
The name of the configuration template\.  
*Required*: Yes  
*Type*: String