controlled-joints: ['FR_hip_motor_2_chassis_joint', 'FR_upper_leg_2_hip_motor_joint', 'FR_lower_leg_2_upper_leg_joint', 'FL_hip_motor_2_chassis_joint', 'FL_upper_leg_2_hip_motor_joint', 'FL_lower_leg_2_upper_leg_joint', 'RR_hip_motor_2_chassis_joint', 'RR_upper_leg_2_hip_motor_joint', 'RR_lower_leg_2_upper_leg_joint', 'RL_hip_motor_2_chassis_joint', 'RL_upper_leg_2_hip_motor_joint', 'RL_lower_leg_2_upper_leg_joint']
actor-action-joints: ['FR_hip_motor_2_chassis_joint', 'FR_upper_leg_2_hip_motor_joint', 'FR_lower_leg_2_upper_leg_joint', 'FL_hip_motor_2_chassis_joint', 'FL_upper_leg_2_hip_motor_joint', 'FL_lower_leg_2_upper_leg_joint', 'RR_hip_motor_2_chassis_joint', 'RR_upper_leg_2_hip_motor_joint', 'RR_lower_leg_2_upper_leg_joint', 'RL_hip_motor_2_chassis_joint', 'RL_upper_leg_2_hip_motor_joint', 'RL_lower_leg_2_upper_leg_joint']
actor-logstd-initial: [[-0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718
  -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718]]
interpolation: False
gating-index: None
max-path-num: 20
total-step-num: 2500000000
gating-activation-fn: ['relu', 'relu', 'None']
joint-interpolation: True
bullet-default-PD: False
HLC-frequency: 25
LLC-frequency: 500
reward-scale: 0.1
action-bounds: [[-0.5236 -2.7925  0.6981 -0.5236 -2.7925  0.6981 -0.5236 -2.7925  0.6981
  -0.5236 -2.7925  0.6981]
 [ 0.5236  0.3491  2.7925  0.5236  0.3491  2.7925  0.5236  0.3491  2.7925
   0.5236  0.3491  2.7925]]
replay-ratio: 1
max-step-num: 2500000000
render-eval: False
actor-l2-reg: 0.0003
max-test-time: 10
filter-torque: False
imitation-weight: 1.0
max-train-time: 10
test-num: 4
n-step: 1
gating-layer-size: [32, 32]
critic-layer-size: [256, 256]
critic-weight-decay: 1e-06
max-episode-num: 5000000
epoch-num: 500
loss-entropy-coeff: 0.0
critic-activation-fn: ['relu', 'relu', 'None']
env-id: HumanoidBalanceFilter-v0
Physics-frequency: 1000
epoch-step-num: 5000000
loss-output-diff-coeff: 0
state-dim: 18
actor-output-bounds: [[-1. -1. -1. -1. -1. -1. -1. -1. -1. -1. -1. -1.]
 [ 1.  1.  1.  1.  1.  1.  1.  1.  1.  1.  1.  1.]]
actor-lr: 0.0003
expert-num: 4
loss-output-smooth-coeff: 2.0
tau: 0.001
actor-logstd-bounds: [[-1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791
  -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791]
 [-0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718
  -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718]]
squash-action: True
action-dim: 12
categorical-distribution: {'v_max': 250, 'v_min': -10, 'n_atoms': 51}
actor-activation-fn: ['relu', 'relu', 'None']
batch-size: 128
rollout-step-num: 1
max-path-step: 5000
gamma: 0.995
normalized-action-bounds: [[0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0.]
 [0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0.]]
replay-buffer-size: 1000000
prioritized-exp-replay: True
loss-output-bound-coeff: 0.0
replay-start-size: 10000
actor-layer-size: [256, 256]
train-step-num: 1
task-weight: 0.0
expert-index: None
critic-lr: 0.0003
critic-l2-reg: 0.0003
actor-weight-decay: 1e-06
record-start-size: 10000.0
filter-action: True
