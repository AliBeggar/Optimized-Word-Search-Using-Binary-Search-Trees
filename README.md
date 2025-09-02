# Optimized Word Search Using BST Variants

A Binary Search Tree optimization implementation for efficient word searching with alphabetic priority handling.

## 📋 Project Overview

This project implements a triplet of optimized Binary Search Trees designed to enhance search performance for words starting with specific alphabetic characters ('Y', 'Z', 'a'). The system uses strategic tree rotations to position frequently searched elements closer to the root for improved access times.

## 🏗️ Architecture

### BST Variants

The project implements four Binary Search Tree variants:

1. **BST1**: Words starting with X='Y', Y='Z', or Z='a' are moved to root using rotations
2. **BST2**: Words starting with X, Y, or Z are moved to middle of search path using rotations  
3. **BST3**: Words NOT starting with X, Y, or Z are moved to root using rotations
4. **BST0**: Standard BST implementation for performance comparison

### Key Features

- **Triple BST Architecture**: Three specialized BST variants with different optimization strategies
- **Alphabetic Priority System**: Optimized for words starting with specific characters
- **Performance Analysis**: Statistical evaluation and comparison tools
- **Range Search Support**: Efficient range query operations
- **File-based Operations**: Support for large-scale word processing

## 📁 Repository Contents

```
├── Sidali_BEGGAR_Souhail_ELFRAIHI_TPZ.c    # C implementation
├── Sidali_BEGGAR_Souhail_ELFRAIHI_TPZ.alg  # Algorithm specification
└── README.md                                # This file
```

## 🔧 Implementation Details

### Search Strategy
The system automatically selects the appropriate BST based on the first character of the search word, optimizing search paths for frequently accessed character ranges.

### Operations Supported
- Single word search across BST triplet
- Range search for word intervals
- Tree construction and verification
- Performance metrics collection
- Statistical analysis and reporting

### Performance Metrics
- Search path length analysis
- Node visitation counting
- Tree depth measurement
- Success/failure rate tracking
- Character distribution analysis

## 🚀 Getting Started

### Prerequisites
- C Compiler (Dev-C++ or Code::Blocks recommended)
- Standard C library support

### Compilation
```bash
gcc -o bst_optimizer Sidali_BEGGAR_Souhail_ELFRAIHI_TPZ.c -std=c99
```

## 📊 Features

### Core Functionality
- **Tree Construction**: Build optimized BSTs from word files
- **Search Operations**: Single word and range search capabilities  
- **Performance Analysis**: Comprehensive statistical evaluation
- **File Processing**: Handle large datasets efficiently
- **Result Visualization**: Generate performance comparison data

### Optimization Techniques
- **Tree Rotations**: Strategic repositioning of nodes
- **Character-based Distribution**: Intelligent BST selection
- **Memory Management**: Efficient storage and retrieval
- **Path Optimization**: Minimized search operations

## 🧪 Testing

The implementation includes comprehensive testing for:
- Tree construction correctness
- Search operation accuracy
- Performance metric calculation
- Range query functionality
- Large dataset handling

## 📈 Academic Context

**Course**: Data Structures  
**Level**: 1st Year Computer Science  
**Year**: 2025  
**Focus**: Advanced BST optimization and performance analysis

### Project Objectives
- Implement efficient BST variants for character-specific optimization
- Analyze and compare search performance across different tree structures
- Develop statistical evaluation tools for algorithmic comparison
- Demonstrate practical applications of tree rotation techniques

## 📚 Technical Specifications

- **Language**: C (Standard C99)
- **Data Structures**: Binary Search Trees with optional parent pointers
- **File Format**: Text-based word files
- **Performance Metrics**: Path length, node visitation, tree depth
- **Character Encoding**: Standard ASCII with case-sensitive ordering

## 👥 Authors

**Sidali BEGGAR** & **Souhail ELFRAIHI**

## 📄 License

This project is developed for academic purposes as part of a Algorithms and Dynamic Data Structures course at ESI (ex. INI).

---

*This implementation focuses on practical BST optimization techniques and performance analysis for character-based word searching systems.*
