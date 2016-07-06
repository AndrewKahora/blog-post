---
layout: post
title: getters and setters
---

Getters and setters in java structures
--------------------------------------

 What are getters and setters?
  This are private attributes that occur under Encapsulation that hide the data attributes and prevent incorrect modification. In practice, it's actually quite simple.

  Getters:
 This returns the current value of an attribute to an external class.

  Setters:
 This will allow an external class to change the value of an attribute.


~~~ java
package javaapplication1.get.and.set;

/**
 *
 * @author andrew
 */
public class JavaApplication1GetAndSet {

    /**
     * @param args the command line arguments
     */
    public static void main(String[] args) {
        // TODO code application logic here


    }
    private int age;

    /**
     * Get the value of string
     *
     * @return the value of string
     */
    public int getAge() {
        return this.age;
    }

    /**
     * Set the value of string
     *
     * @param age new value of string
     */
    public void setAge(int age) {
        this.age = age;
    }
  }
