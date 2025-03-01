# Internship Knowledge Map

## Technical Architecture & Frameworks

### ReAct Architecture
- [[English_Internship_Logs/36|Design and Implementation of an Intelligent Regulatory Compliance Review System]] - Introduces the basic principles and implementation of ReAct (Reasoning + Acting) architecture
  - Reasoning-Action-Observation loop
  - Think-Tool Call-Result Processing design pattern
  - Multi-turn conversation management
- [[English_Internship_Logs/37|Design and Implementation of an LLM-Based Intelligent Advertisement Review System]] - Demonstrates the application of ReAct architecture in advertisement review
  - Scene recognition module design
  - Parallel tool calling implementation
  - Result merging and final decision making
- [[English_Internship_Logs/41|Building a Reliable LLM Tool Calling System]] - Explores in-depth the reliability issues in tool calling within ReAct architecture
  - Tool call state management
  - Result validation and consistency guarantees
  - Early stopping strategies and efficiency optimizations

### Modular System Design
- [[English_Internship_Logs/36|Design and Implementation of an Intelligent Regulatory Compliance Review System]] - Introduces layered modular design
  - Collaboration between rule parser, review controller, and tool integration layer
  - Interface design between modules
- [[English_Internship_Logs/40|Health Food Advertisement Intelligent Review System]] - Demonstrates layered design in complex business systems
  - Division into access layer, business layer, model layer, and infrastructure layer
  - Responsibilities and collaboration mechanisms between layers
- [[English_Internship_Logs/37|Design and Implementation of an LLM-Based Intelligent Advertisement Review System]] - Discusses inter-module communication and integration
  - Collaboration between scene recognition module, rule parsing module, and ReAct controller
  - Asynchronous communication mechanisms

### FastAPI Application Development
- [[English_Internship_Logs/26|FastAPI Image Comparison Development and Optimization]] - Introduces basic application of FastAPI framework
  - Route definition and parameter validation
  - Asynchronous processing capabilities
  - Dependency injection system
- [[English_Internship_Logs/29|FastAPI System Error Handling and Robustness Optimization]] - Discusses error handling mechanisms in FastAPI in detail
  - Global exception handlers
  - Middleware design
  - Response model standardization
- [[English_Internship_Logs/40|Health Food Advertisement Intelligent Review System]] - Demonstrates FastAPI application in complex business systems
  - Large application structure organization
  - API version management
  - File upload and processing

## Large Language Model Applications

### Prompt Engineering
- [[English_Internship_Logs/36|Design and Implementation of an Intelligent Regulatory Compliance Review System]] - Introduces template-based prompt management
  - Template design principles
  - Dynamic parameter replacement
  - Context management
- [[English_Internship_Logs/41|Building a Reliable LLM Tool Calling System]] - Discusses in detail how to design prompts to guide LLMs to use tools correctly
  - Formatted tool usage instructions
  - Clear step-by-step guidance
  - Example-driven prompt design
- [[English_Internship_Logs/37|Design and Implementation of an LLM-Based Intelligent Advertisement Review System]] - Demonstrates the application of structured prompt templates
  - Task description optimization
  - Standardized tool descriptions
  - Output format control
- [[English_Internship_Logs/45|Rule Structure Optimization and Simplification]] - Discusses how to design prompts for structured output
  - JSON format control techniques
  - Field constraint descriptions
  - Correspondence between prompt structure and output structure

### Tool Calling
- [[English_Internship_Logs/41|Building a Reliable LLM Tool Calling System]] - Analyzes in depth the reliability issues in LLM tool calling
  - Tool call parsing techniques
  - Result validation mechanisms
  - Retry and fault tolerance handling
- [[English_Internship_Logs/36|Design and Implementation of an Intelligent Regulatory Compliance Review System]] - Demonstrates the design of the tool integration layer
  - Tool registration mechanisms
  - Parameter validation and conversion
  - Result standardization processing
- [[English_Internship_Logs/37|Design and Implementation of an LLM-Based Intelligent Advertisement Review System]] - Introduces tool calling implementation in the ReAct controller
  - Dynamic tool selection
  - Parameter construction
  - Result processing workflow
- [[English_Internship_Logs/40|Health Food Advertisement Intelligent Review System]] - Discusses domain-specific tool design and implementation
  - Logo detection tools
  - Text analysis tools
  - Compliance verification tools

### Multimodal Analysis
- [[English_Internship_Logs/26|FastAPI Image Comparison Development and Optimization]] - Introduces the application of vision language models in image analysis
  - Image feature extraction
  - Semantic-level comparison analysis
  - Similarity calculation methods
- [[English_Internship_Logs/37|Design and Implementation of an LLM-Based Intelligent Advertisement Review System]] - Demonstrates multimodal analysis in advertisement review
  - Combined text-image analysis
  - Multimodal content understanding
  - Cross-modal feature fusion
- [[English_Internship_Logs/40|Health Food Advertisement Intelligent Review System]] - Details the implementation of the image analysis module
  - Image preprocessing techniques
  - Feature extraction and matching
  - Image block processing optimization

### LLM Output Parsing and Post-processing
- [[English_Internship_Logs/26|FastAPI Image Comparison Development and Optimization]] - Discusses JSON output cleaning and standardization
  - Format repair techniques
  - Structure validation methods
  - Error recovery strategies
- [[English_Internship_Logs/41|Building a Reliable LLM Tool Calling System]] - Introduces tool call parsing techniques
  - String matching methods
  - Parsing error handling
  - Incremental parsing strategies
- [[English_Internship_Logs/37|Design and Implementation of an LLM-Based Intelligent Advertisement Review System]] - Demonstrates complex decision result extraction methods
  - Final result standardization
  - Evidence chain extraction
  - Explainability enhancement

## Data Processing & Validation

### Rule Parsing
- [[English_Internship_Logs/42|Design and Evolution of a Rule Parser]] - Details the design approach and evolution process of the rule parser
  - LLM integration with rule parsing
  - Parsing result validation
  - Incremental update mechanisms
- [[English_Internship_Logs/43|Intelligent Segmentation Processing for Large-Scale Regulatory Texts]] - Discusses technical solutions for processing large-scale regulatory texts
  - Intelligent segmentation algorithms
  - Context preservation strategies
  - Segment merging techniques
- [[English_Internship_Logs/36|Design and Implementation of an Intelligent Regulatory Compliance Review System]] - Introduces the basic functionality of the rule parser
  - Regulatory text structuring
  - Rule extraction and classification
  - Rule applicability assessment
- [[English_Internship_Logs/45|Rule Structure Optimization and Simplification]] - Analyzes in detail the evolution process of rule structures from complexity to simplicity
  - Structure redundancy analysis
  - Field optimization strategies
  - Data migration solutions

### Data Models
- [[English_Internship_Logs/44|Rule Model Design Based on Pydantic]] - Details building type-safe data models using Pydantic
  - Field validation mechanisms
  - Custom validators
  - Model nesting and composition
- [[English_Internship_Logs/26|FastAPI Image Comparison Development and Optimization]] - Demonstrates Pydantic data models in FastAPI applications
  - Request/response model design
  - Automatic model documentation generation
  - Model serialization and deserialization
- [[English_Internship_Logs/42|Design and Evolution of a Rule Parser]] - Discusses simplification and optimization of rule structures
  - Model evolution strategies
  - Backward compatibility guarantees
  - Model version management
- [[English_Internship_Logs/45|Rule Structure Optimization and Simplification]] - Shows the impact of data model optimization on system performance
  - Field selection and organization
  - Flattened structure design
  - Validation logic optimization

### Text Processing
- [[English_Internship_Logs/43|Intelligent Segmentation Processing for Large-Scale Regulatory Texts]] - Details text segmentation and context maintenance techniques
  - Rule-based segmentation
  - Dynamic length adjustment
  - Context window mechanisms
- [[English_Internship_Logs/38|Python Implementation for Batch Residential Community Data Analysis]] - Demonstrates address information extraction and text processing techniques
  - Address parsing algorithms
  - Data cleaning techniques
  - Information extraction strategies
- [[English_Internship_Logs/39|Python Automation for Old Residential Community Analysis]] - Introduces the application of regular expressions in text processing
  - Multi-level extraction strategies
  - Pattern matching optimization
  - Text data validation

### JSON Processing
- [[English_Internship_Logs/26|FastAPI Image Comparison Development and Optimization]] - Details JSON cleaning and standardization
  - Field repair techniques
  - Format standardization methods
  - Complex nested structure handling
- [[English_Internship_Logs/41|Building a Reliable LLM Tool Calling System]] - Discusses JSON parsing and validation
  - Partial parsing strategies
  - Error recovery mechanisms
  - Result validation techniques
- [[English_Internship_Logs/42|Design and Evolution of a Rule Parser]] - Demonstrates JSON data conversion and storage
  - Serialization optimization
  - Compression strategies
  - Version compatibility handling

## System Optimization & Best Practices

### Performance Optimization
- [[English_Internship_Logs/43|Intelligent Segmentation Processing for Large-Scale Regulatory Texts]] - Introduces parallel processing and cache optimization techniques
  - Task splitting strategies
  - Parallel execution control
  - Result merging mechanisms
- [[English_Internship_Logs/42|Design and Evolution of a Rule Parser]] - Discusses asynchronous processing and caching mechanisms
  - I/O-intensive operation optimization
  - Resource pool management
  - Asynchronous task scheduling
- [[English_Internship_Logs/40|Health Food Advertisement Intelligent Review System]] - Demonstrates optimization of image processing and concurrent processing
  - Image preprocessing optimization
  - Memory usage optimization
  - Concurrent request management
- [[English_Internship_Logs/45|Rule Structure Optimization and Simplification]] - Analyzes in detail the significant performance improvements from data structure optimization
  - Performance benefits of structure simplification
  - Parsing speed improvements
  - Storage space savings

### Error Handling
- [[English_Internship_Logs/29|FastAPI System Error Handling and Robustness Optimization]] - Details multi-level error handling mechanisms
  - Exception classification system
  - Global exception handlers
  - Error response standardization
- [[English_Internship_Logs/41|Building a Reliable LLM Tool Calling System]] - Discusses error handling in LLM tool calling
  - Parsing error handling
  - Tool execution error recovery
  - State consistency guarantees
- [[English_Internship_Logs/37|Design and Implementation of an LLM-Based Intelligent Advertisement Review System]] - Demonstrates multi-level exception catching and retry mechanisms
  - Tiered retry strategies
  - Timeout handling
  - Degradation mechanisms
- [[English_Internship_Logs/40|Health Food Advertisement Intelligent Review System]] - Introduces system-level error handling design
  - Error classification strategies
  - Logging standards
  - Monitoring and alerting integration

### Caching Strategies
- [[English_Internship_Logs/42|Design and Evolution of a Rule Parser]] - Introduces text hash-based caching mechanisms
  - Cache key design
  - Cache expiration strategies
  - Cache consistency guarantees
- [[English_Internship_Logs/43|Intelligent Segmentation Processing for Large-Scale Regulatory Texts]] - Discusses segment-level cache optimization
  - Fine-grained cache design
  - Cache hit rate optimization
  - Memory and persistent cache combination
- [[English_Internship_Logs/40|Health Food Advertisement Intelligent Review System]] - Demonstrates caching application for image analysis results
  - Multi-level cache design
  - Cache warming strategies
  - Cache update mechanisms
- [[English_Internship_Logs/41|Building a Reliable LLM Tool Calling System]] - Discusses LLM response caching optimization
  - Prompt hash caching
  - Result reuse strategies
  - Cache invalidation mechanisms

### Data Migration & Refactoring
- [[English_Internship_Logs/45|Rule Structure Optimization and Simplification]] - Details the design and implementation of data migration tools
  - Field mapping strategies
  - Incremental migration techniques
  - Data validation mechanisms
- [[English_Internship_Logs/42|Design and Evolution of a Rule Parser]] - Discusses refactoring strategies during system evolution
  - Gradual refactoring methods
  - Interface compatibility maintenance
  - Feature migration steps
- [[English_Internship_Logs/44|Rule Model Design Based on Pydantic]] - Demonstrates validation mechanisms in model refactoring
  - Data converters
  - Model compatibility layers
  - Validation logic migration

### Asynchronous Programming Patterns
- [[English_Internship_Logs/26|FastAPI Image Comparison Development and Optimization]] - Introduces asynchronous processing patterns in FastAPI
  - Asynchronous route design
  - Asynchronous dependency injection
  - Asynchronous context management
- [[English_Internship_Logs/29|FastAPI System Error Handling and Robustness Optimization]] - Discusses error handling in asynchronous systems
  - Asynchronous exception propagation
  - Task cancellation handling
  - Timeout management
- [[English_Internship_Logs/41|Building a Reliable LLM Tool Calling System]] - Demonstrates complex asynchronous flow control
  - Asynchronous state management
  - Asynchronous tool calling
  - Asynchronous result aggregation

## Testing & Monitoring

### Testing Strategies
- [[English_Internship_Logs/29|FastAPI System Error Handling and Robustness Optimization]] - Discusses system robustness testing methods
  - Exception injection testing
  - Boundary condition testing
  - Load testing
- [[English_Internship_Logs/41|Building a Reliable LLM Tool Calling System]] - Introduces LLM tool calling testing techniques
  - Tool response simulation
  - Exception scenario testing
  - Integration test design
- [[English_Internship_Logs/40|Health Food Advertisement Intelligent Review System]] - Demonstrates testing strategies for complex systems
  - Modular testing
  - End-to-end testing
  - Performance benchmark testing

### Logging & Monitoring
- [[English_Internship_Logs/29|FastAPI System Error Handling and Robustness Optimization]] - Details logging system design
  - Log level strategies
  - Structured logging
  - Contextual logging
- [[English_Internship_Logs/41|Building a Reliable LLM Tool Calling System]] - Discusses tool call logging and monitoring
  - Key point logging
  - Performance metric collection
  - Anomaly pattern detection
- [[English_Internship_Logs/40|Health Food Advertisement Intelligent Review System]] - Demonstrates multi-level monitoring systems
  - System monitoring
  - Business monitoring
  - Performance monitoring
  - Security monitoring

## Engineering Practices & Project Management

### Code Organization & Design Patterns
- [[English_Internship_Logs/26|FastAPI Image Comparison Development and Optimization]] - Introduces modular design and code organization
  - Service layering pattern
  - Separation of concerns principle
  - Dependency injection pattern
- [[English_Internship_Logs/41|Building a Reliable LLM Tool Calling System]] - Discusses the application of controller pattern in tool calling
  - State management pattern
  - Command pattern
  - Strategy pattern
- [[English_Internship_Logs/40|Health Food Advertisement Intelligent Review System]] - Demonstrates code organization for large systems
  - Modular design
  - Interface design principles
  - Configuration management strategies

### Version Management & Evolution
- [[English_Internship_Logs/42|Design and Evolution of a Rule Parser]] - Discusses system version evolution strategies
  - Backward compatibility guarantees
  - Gradual updates
  - Feature toggle mechanisms
- [[English_Internship_Logs/45|Rule Structure Optimization and Simplification]] - Demonstrates data structure evolution management
  - Architecture refactoring planning
  - Migration strategies
  - Transitional dual-system operation
- [[English_Internship_Logs/44|Rule Model Design Based on Pydantic]] - Introduces data model version management
  - Model version control
  - Field deprecation strategies
  - Default value evolution 