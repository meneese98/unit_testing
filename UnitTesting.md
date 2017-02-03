```java
public class Car
{
  drive()
  {
    Start car();
    put seatbelt on();
    put in gear();
    accelerate();
    turn();
    brake();
  }

  startCar()
  {
    checkSourceOfIgnition

    if(key)
    {
      put into ignition; //imperative
      turn;
    }

    if(car)
    {
      press gas;
    }
    else
    {
      pressButton;
    }
  }

  putSeatbeltOn()
  {
    grab seat belt;
    click it or ticket;
  }

  putInGear
  {
    if(manual)
    {
      shiftManual();
    }
    else
    {
      shiftAuto();
    }
  }

  shiftManual()
  {
    pressClutch();
    moveGearShift(gear);
    releaseClutch();
  }

  workClutch(boolean press)
  {
    if(press)
    {
      //do steps to press
      isClutchPress = true
    }
    else
    {
      //do steps to release
      isClutchPress = false
    }
  }

  void testWorkClutch()
  {
      workCluch(true);
      assert(isClutchPressed);
      workClutch(false);
      assert(! isClutchPressed);
  }
}

//DO NOT put everything into the main method.  Break code down into smaller methods.
