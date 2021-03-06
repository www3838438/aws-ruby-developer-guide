.. Copyright 2010-2017 Amazon.com, Inc. or its affiliates. All Rights Reserved.

   This work is licensed under a Creative Commons Attribution-NonCommercial-ShareAlike 4.0
   International License (the "License"). You may not use this file except in compliance with the
   License. A copy of the License is located at http://creativecommons.org/licenses/by-nc-sa/4.0/.

   This file is distributed on an "AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND,
   either express or implied. See the License for the specific language governing permissions and
   limitations under the License.

.. _aws-ruby-sdk-sqs-example-redirect-deadletters:

#################################
Redirecting Dead Letters in |SQS|
#################################

.. meta::
   :description:
        Redirect dead letters from one SQS queue to another using this AWS SDK for Ruby code example.
   :keywords: AWS SDK for Ruby code examples, SQS

The following example redirects any dead letters from the queue with the URL :code:`URL` to the
queue with the ARN :code:`ARN`.

.. literalinclude:: ./example_code/sqs/sqs-ruby-example-redirect-queue-deadletters.rb
   :lines: 13-23
   :dedent: 0
   :language: ruby
