.. _safety:

Safety
======

.. _lipo_battery_safety:

LiPo battery handling
^^^^^^^^^^^^^^^^^^^^^

The boat uses a large capacity lithium polymer (LiPo) :ref:`battery<lipo_battery>`.
Aside from the large capacity, this is a typical RC hobbyist battery.
With proper handling and avoiding abuse, the LiPo batteries are
not safety hazards. However, if they are mishandled or abused,
they can create fire hazards.

For a comprehensive guide on LiPo batteries, read https://rogershobbycenter.com/lipoguide/.

A LiPo has five important voltage levels:

#. Peak = 4.2 V per cell (16.8 V for a 4S battery)
#. Storage = 3.8 V per cell (15.2 V for a 4S batter)
#. Nominal = 3.7 V per cell (14.8 V for a 4S battery)
#. Drained = 3.5 V per cell (14 V for a 4S battery)
#. Damaged = 3.0 V per cell (12 V for a 4S battery)

When operating the boat, not drain the boat's battery below
the "Drained" voltage if at all possible.
Draining it below this value should be done only if 
you need to recover the boat.
It is hard to predict how draining the battery below 3.5 V per cell
can affect the long-term health of the battery,
so it is best to avoid it entirely.

*NEVER* drain the battery to the "Damaged" voltage or lower!
Doing so can lead to the battery entering a state where
physical impact can puncture the cells, creating a serious fire hazard!

If a LiPo battery is drained too far, it will become "puffy".
Normally the battery will be a rigid brick of materials,
but a puffy battery will have expanded like a ballon.

*NEVER* recharge or use a puffy LiPo battery!


General electrical circuit handling
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

The boat's battery is capable of a very large output current,
especially in the case of an electrical short.

Avoid directly touching any circuit boards while the battery is connected to the boat.
Unless otherwise noted, only *cables*, *connectors*, *buttons*, and *switches* 
are meant to be handled.


Voltage regulator residual charge
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

The :ref:`BlueBox<bluebox>` uses a :ref:`24 V voltage regulator<bluebox_power>`
to convert from the battery's voltage to a steady 24 V. The voltage regulator
can hold a residual charge. Even after the battery has been unplugged, the
:ref:`cable's<cable_harness_and_breaker>` XT90 connector (the large yellow connector)
can produce a significant electrical shock.

When unplugging the battery, ensure that the two metal leads inside the XT90 connector 
do not come into contact with anything conductive. This is easy - just set the
cable down gently into the rear compartment after unplugging the battery.

The residual charge will slowly drain away on its own, but this process can be sped up.
To quickly drain the charge, after the battery is disconnected you can turn on the
:ref:`BlueBox power switch<bluebox_power>` for 5 seconds, then turn it off. 
This will consume the vast majority of the residual charge.


Water in the internal compartments
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

As noted above, electrical shorts are a risk for any electrical
system. Water entering the compartments, especially the front
compartment, can cause electrical shorts between any of the
electronics installed there.

It is common to have a small amount of water in the rear
compartment, but the front compartment should remain dry.
If you see water in the front compartment, immediately shut off
the boat, remove the battery, and dry the components!

Try to identify the leak ingress point - there is something
very wrong if you see water in the front compartment!

One common way water can enter the front compartment is if the
white housing lid is dripping wet and you hold it over the
open compartment. If you are about to open the front compartment,
make sure the lid is dry.

Fast-spinning propellers
^^^^^^^^^^^^^^^^^^^^^^^^

Simple rule - never directly touch the motors, propellers, 
or airfan while the boat is on.

When you are inspecting the propellers, set the boat down so that the
propellers are free to spin in the air.



:ref:`Back to the index <index>`