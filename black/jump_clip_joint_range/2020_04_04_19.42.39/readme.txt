squash-action: True
loss-output-smooth-coeff: 2.0
max-path-num: 20
prioritized-exp-replay: True
imitation-weight: 0.5
actor-logstd-initial: [[-0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718
  -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718]]
max-train-time: 10
replay-ratio: 1
critic-layer-size: [256, 256]
HLC-frequency: 25
train-step-num: 1
gating-index: None
actor-action-joints: ['FR_hip_motor_2_chassis_joint', 'FR_upper_leg_2_hip_motor_joint', 'FR_lower_leg_2_upper_leg_joint', 'FL_hip_motor_2_chassis_joint', 'FL_upper_leg_2_hip_motor_joint', 'FL_lower_leg_2_upper_leg_joint', 'RR_hip_motor_2_chassis_joint', 'RR_upper_leg_2_hip_motor_joint', 'RR_lower_leg_2_upper_leg_joint', 'RL_hip_motor_2_chassis_joint', 'RL_upper_leg_2_hip_motor_joint', 'RL_lower_leg_2_upper_leg_joint']
filter-action: True
action-dim: 12
replay-buffer-size: 1000000
bullet-default-PD: False
actor-activation-fn: ['relu', 'relu', 'None']
LLC-frequency: 500
critic-activation-fn: ['relu', 'relu', 'None']
filter-torque: False
actor-layer-size: [256, 256]
gamma: 0.955
actor-logstd-bounds: [[-1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791
  -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791]
 [-0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718
  -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718]]
loss-output-diff-coeff: 0
gating-activation-fn: ['relu', 'relu', 'None']
tau: 0.001
normalized-action-bounds: [[0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0.]
 [0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0.]]
controlled-joints: ['FR_hip_motor_2_chassis_joint', 'FR_upper_leg_2_hip_motor_joint', 'FR_lower_leg_2_upper_leg_joint', 'FL_hip_motor_2_chassis_joint', 'FL_upper_leg_2_hip_motor_joint', 'FL_lower_leg_2_upper_leg_joint', 'RR_hip_motor_2_chassis_joint', 'RR_upper_leg_2_hip_motor_joint', 'RR_lower_leg_2_upper_leg_joint', 'RL_hip_motor_2_chassis_joint', 'RL_upper_leg_2_hip_motor_joint', 'RL_lower_leg_2_upper_leg_joint']
expert-index: None
render-eval: False
n-step: 1
record-start-size: 10000.0
total-step-num: 2500000000
loss-entropy-coeff: 0.0
replay-start-size: 10000
actor-weight-decay: 1e-06
actor-lr: 0.0003
batch-size: 128
max-step-num: 2500000000
categorical-distribution: {'n_atoms': 51, 'v_max': 250, 'v_min': -10}
joint-interpolation: True
interpolation: False
gating-layer-size: [32, 32]
critic-weight-decay: 1e-06
epoch-step-num: 5000000
max-test-time: 10
loss-output-bound-coeff: 0.0
actor-l2-reg: 0.0003
rollout-step-num: 1
state-dim: 23
critic-lr: 0.0003
max-path-step: 5000
actor-output-bounds: [[-1. -1. -1. -1. -1. -1. -1. -1. -1. -1. -1. -1.]
 [ 1.  1.  1.  1.  1.  1.  1.  1.  1.  1.  1.  1.]]
test-num: 4
critic-l2-reg: 0.0003
dsr-gait-period: 0.6
dsr-gait-freq: 1.667
reward-scale: 0.1
Physics-frequency: 1000
expert-num: 4
env-id: HumanoidBalanceFilter-v0
task-weight: 0.5
max-episode-num: 5000000
action-bounds: [[-0.5236 -2.7925  0.6981 -0.5236 -2.7925  0.6981 -0.5236 -2.7925  0.6981
  -0.5236 -2.7925  0.6981]
 [ 0.5236  0.3491  2.7925  0.5236  0.3491  2.7925  0.5236  0.3491  2.7925
   0.5236  0.3491  2.7925]]
epoch-num: 500
