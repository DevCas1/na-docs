AnimatorParam
=============
Select an Animator paramater via dropdown interface::

    public class NaughtyComponent : MonoBehaviour
    {
        public Animator someAnimator;

        [AnimatorParam(nameOf(someAnimator))]
        public int paramHash;

        [AnimatorParam(nameOf(someAnimator))]
        public string paramName;
    }

.. image:: ../../images/AnimatorParam_Inspector.png
